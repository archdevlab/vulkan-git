## vulkan-git

**Vulkan package suite for Archlinux (git version)**

Contains all Vulkan packages suite from Archlinux build directly from KhronosGroup git repos

#### List of Packages
- vulkan-headers-git
- vulkan-utility-libraries-git
- lib32-vulkan-utility-libraries-git
- volk-git
- lib32-volk-git
- vulkan-icd-loader-git
- lib32-vulkan-icd-loader-git
- vulkan-validation-layers-git
- lib32-vulkan-validation-layers-git
- vulkan-extensionlayer-git
- lib32-vulkan-extensionlayer-git
- vulkan-tools-git

### Prebuild package

Prebuild package are available at https://repo.archdevlab.org/x86_64/vulkan-git

You can add this repo to your pacman.conf

    [vulkan-git]
    SigLevel = Optional TrustAll
    Server = https://repo.archdevlab.org/$arch/$repo
