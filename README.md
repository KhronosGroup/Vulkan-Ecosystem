# Vulkan-Ecosystem
This repository is used as a tracker for cross-functional issues that affect
Vulkan users. It is meant to facilitate triaging, discussion and routing of
issues that don't necessarily fit under the scope of a single project within
the Vulkan ecosystem.

# Map of Vulkan Ecosystem projects
The Vulkan ecosystem is a big place and there's a lot out there that is useful! In no particular order...

## RenderDoc
RenderDoc - a graphics debugger, currently available for Vulkan, D3D11, D3D12, and OpenGL development on Windows 7 - 10 and Linux.

* Website: https://renderdoc.org/
* Repository: https://github.com/baldurk/renderdoc
* License: [MIT](https://github.com/baldurk/renderdoc/blob/v0.x/LICENSE.md)
* Contacts:
    * baldurk@baldurk.org
    * [#renderdoc on freenode IRC](https://kiwiirc.com/client/irc.freenode.net/#renderdoc)
* Code of conduct: [contributor covenant](https://github.com/baldurk/renderdoc/blob/v0.x/CODE_OF_CONDUCT.md)
* Compiler requirements: MSVC 2015 / gcc 5 / clang 3.4

## SPIRV-Tools
The SPIR-V Tools project provides an API and commands for processing SPIR-V modules.

* Repository: https://github.com/KhronosGroup/SPIRV-Tools
* License: [Apache](https://github.com/KhronosGroup/SPIRV-Tools/blob/master/LICENSE)
* Contacts:
    * https://www.khronos.org/spir/spirv-tools-mailing-list/
    * David Neto <dneto@google.com>
* Compiler requirements: C++11 compatible compiler (MSVC 2013+ on Windows)

## glslang
glslang is a GLSL and HLSL to SPIR-V compiler, usable both as a command-line tool as well as a library.

* Website: https://www.khronos.org/opengles/sdk/tools/Reference-Compiler/
* Repository: https://github.com/KhronosGroup/glslang
* License: 3-clause BSD
* Contact: David Neto <dneto@google.com>
* Compiler requirements: C++11 compatible compiler (MSVC 2013+ on Windows)

## Vulkan-LoaderAndValidationLayers
Source code for the Vulkan loader and validation layers, Vulkan API header files, demos and tests.

* Repository: https://github.com/KhronosGroup/Vulkan-LoaderAndValidationLayers
* License: [Apache](https://github.com/KhronosGroup/Vulkan-LoaderAndValidationLayers/blob/master/LICENSE.txt)
* Contacts:
    * Tobine Ehlis <tobine@google.com>
    * Mark Lobodzinski <mark@lunarg.com>
* Code of conduct: https://github.com/KhronosGroup/Vulkan-LoaderAndValidationLayers/blob/master/GOVERNANCE.md
* Compiler requirements: MSVC 2013+ / gcc 4.8.2+ / clang 3.4+

## VulkanTools
Source code for various Vulkan Tools: vktrace/vkreplay, device simulation layer, API dump layer, fps monitor layer, screenshot layer, assistant layer, layer factory framework, and Vulkan installation analyzer.

* Repository: https://github.com/LunarG/VulkanTools
* License: [Apache](https://github.com/LunarG/VulkanTools/blob/master/LICENSE.txt)
* Contact: David Pinedo <david@lunarg.com>
* Code of conduct: https://github.com/LunarG/VulkanTools/blob/master/GOVERNANCE.md
* Compiler requirements: MSVC 2013+ / gcc 4.8.2+ / clang 3.4+

## Vulkan-HPP
Vulkan-Hpp is a set of lightweight C++ bindings for the Vulkan API.

* Repository: https://github.com/KhronosGroup/Vulkan-Hpp
* License: [Apache](https://github.com/KhronosGroup/Vulkan-Hpp/blob/master/LICENSE.txt)
* Compiler requirements: MSVC 2015+ / gcc 4.8.2+ / clang 3.3+
* Contact: Markus Tavenrath <mtavenrath@nvidia.com>
