# Vulkan-Ecosystem
This repository is used as a tracker for cross-functional issues that affect
Vulkan users. It is meant to facilitate triaging, discussion and routing of
issues that don't necessarily fit under the scope of a single project within
the Vulkan ecosystem.

# Map of Vulkan Ecosystem projects
Vulkan ecosystem is a big place, but there's a lot out there that is useful! In no particular order...

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
    * dneto@google.com

## gfx-rs
gfx-rs is Vulkan-ic graphics abstraction layer in Rust, running on Vulkan, D3D12, Metal, and OpenGL, as well as providing [C bindings](https://github.com/gfx-rs/portability) as a Vulkan Portability implementation.

* Repository: https://github.com/gfx-rs/gfx
* License: [Apache](https://github.com/gfx-rs/gfx/blob/master/LICENSE-APACHE) or [MIT](https://github.com/gfx-rs/gfx/blob/master/LICENSE-MIT)
* Contacts:
  * [gfx-rs on Gitter](https://gitter.im/gfx-rs/gfx)
  * [Dzmitry Malyshau](mailto:kvarkus@gmail.com)
* Compiler requirements: Rust 1.22, gcc 5 / clang 3.4 for the portability layer

## Vulkano
Vulkano is a type-safe wrapper around Vulkan API in Rust.

* Website: http://vulkano.rs/
* Repository: https://github.com/vulkano-rs/vulkano
* License: [Apache](https://github.com/vulkano-rs/vulkano/blob/master/LICENSE-APACHE) or [MIT](https://github.com/vulkano-rs/vulkano/blob/master/LICENSE-MIT)
* Contacts:
  * [Vulkano on Gitter](https://gitter.im/vulkano-rs/Lobby)
* Compiler requirements: Rust 1.22, gcc-4.8
