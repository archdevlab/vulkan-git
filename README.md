## vulkan-git

**Vulkan package suite for Archlinux (git version)**

Contains all Vulkan packages suite from Archlinux build directly from KhronosGroup git repos

#### List of Packages
- vulkan-headers-git
- vulkan-icd-loader-git
- lib32-vulkan-icd-loader-git
- vulkan-validation-layers-git
- lib32-vulkan-validation-layers-git

### Prebuild package

Prebuild package are available at https://repo.ardevlab.xyz/x86_64/vulkan-git

You can add this repo to your pacman.conf

    [vulkan-git]
    SigLevel = Optional TrustAll
    Server = https://repo.ardevlab.xyz/$arch/$repo
