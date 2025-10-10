# ChaosOS &nbsp; [![bluebuild build badge](https://github.com/blue-build/template/actions/workflows/build.yml/badge.svg)](https://github.com/blue-build/template/actions/workflows/build.yml)

See the [BlueBuild docs](https://blue-build.org/how-to/setup/) for quick setup instructions for setting up your own repository based on this template.

After setup, it is recommended you update this README to describe your custom image.

## Installation
> [INFO]
> 
> These images are not for a main production machine 

To rebase an existing atomic Fedora installation to the latest build:

- To rebase to the unsigned image
  ```
  rpm-ostree rebase ostree-unverified-registry:ghcr.io/blue-build/template:latest
  ```
- Reboot to complete the rebase:
  ```
  systemctl reboot
  ```

## ISO

Coming Soon

## Verification
> [!WARNING]
> These images NOT signed
>
> (update 1 day later after the original warning massage)
>
> these images are now signed
