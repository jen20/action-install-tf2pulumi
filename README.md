# Install `tf2pulumi` Action

This repository contains an action for use with GitHub Actions, which installs a specified version of `tf2pulumi` on Linux.

`tf2pulumi` is installed into `$(go env GOPATH)/bin`, however this directory is not added to the `PATH`.

## Usage

```yaml
- name: Install tf2pulumi
  uses: jen20/install-tf2pulumi@releases/v1
  with:
    tf2pulumi-version: 0.6.0
```
