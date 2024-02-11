## vulkan-git

**Vulkan package suite for Archlinux (git version)**

Contains all Vulkan packages suite from Archlinux build directly from KhronosGroup git repos

#### List of Packages in build order

- vulkan-headers-git
- vulkan-icd-loader-git
- lib32-vulkan-icd-loader-git
- vulkan-utility-libraries-git
- lib32-vulkan-utility-libraries-git
- vulkan-validation-layers-git
- lib32-vulkan-validation-layers-git
- volk-git
- lib32-volk-git
- vulkan-extensionlayer-git
- lib32-vulkan-extensionlayer-git
- vulkan-tools-git
- vulkan-lunarg-tools-git
- valijson-git
- jsoncpp-cmake-git
- lib32-jsoncpp-cmake-git
- vulkan-profiles-git
- lib32-vulkan-profiles-git
- vulkan-wsi-layer-git
- lib32-vulkan-wsi-layer-git

### Prebuild package

Prebuild package are available at https://repo.archdevlab.org/x86_64/vulkan-git

You can add this repo to your pacman.conf

    [vulkan-git]
    SigLevel = Optional TrustAll
    Server = https://repo.archdevlab.org/$arch/$repo
