# Portability WGPU

Subset of Vulkan needed to be implemented:

```
vkAccessFlags
vkAcquireNextImageKHR
vkAdapter
vkAllocateCommandBuffers
vkAllocateDescriptorSets
vkAllocateMemory
vkBarrierBufferSlice
vkBarrierImageSlice
vkBarrierSet
vkBeginCommandBuffer
vkBindBufferMemory
vkBindImageMemory
vkBuffer
vkBuffer>
vkBufferSlice
vkBufferSliceHandle
vkBufferTracker
vkBufferView
vkCmdBeginConditionalRenderingEXT
vkCmdBeginDebugUtilsLabelEXT
vkCmdBeginQuery
vkCmdBeginQueryIndexedEXT
vkCmdBeginRenderPass
vkCmdBeginTransformFeedbackEXT
vkCmdBindDescriptorSets
vkCmdBindIndexBuffer
vkCmdBindPipeline
vkCmdBindTransformFeedbackBuffersEXT
vkCmdBindVertexBuffers
vkCmdBindVertexBuffers2EXT
vkCmdBlitImage
vkCmdClearAttachments
vkCmdClearColorImage
vkCmdClearDepthStencilImage
vkCmdCopyBuffer
vkCmdCopyBufferToImage
vkCmdCopyImage
vkCmdCopyImageToBuffer
vkCmdCopyQueryPoolResults
vkCmdCuLaunchKernelNVX
vkCmdDispatch
vkCmdDispatchIndirect
vkCmdDraw
vkCmdDrawIndexed
vkCmdDrawIndexedIndirect
vkCmdDrawIndexedIndirectCountKHR
vkCmdDrawIndirect
vkCmdDrawIndirectByteCountEXT
vkCmdDrawIndirectCountKHR
vkCmdEndConditionalRenderingEXT
vkCmdEndDebugUtilsLabelEXT
vkCmdEndQuery
vkCmdEndQueryIndexedEXT
vkCmdEndRenderPass
vkCmdEndTransformFeedbackEXT
vkCmdFillBuffer
vkCmdInsertDebugUtilsLabelEXT
vkCmdPipelineBarrier
vkCmdPushConstants
vkCmdResetQueryPool
vkCmdResolveImage
vkCmdSetBlendConstants
vkCmdSetDepthBias
vkCmdSetDepthBounds
vkCmdSetEvent
vkCmdSetScissor
vkCmdSetStencilReference
vkCmdSetViewport
vkCmdUpdateBuffer
vkCmdWriteTimestamp
vkCommandList
vkComputePipeline
vkComputePipelineInstance
vkComputePipelineStateInfo
vkContext
vkContextFlags
vkCreateBuffer
vkCreateBufferView
vkCreateCommandPool
vkCreateComputePipelines
vkCreateCuFunctionNVX
vkCreateCuModuleNVX
vkCreateDescriptorPool
vkCreateDescriptorSetLayout
vkCreateDescriptorUpdateTemplate
vkCreateDevice
vkCreateEvent
vkCreateFence
vkCreateFramebuffer
vkCreateGraphicsPipelines
vkCreateImage
vkCreateImageView
vkCreateInstance
vkCreatePipelineCache
vkCreatePipelineLayout
vkCreateQueryPool
vkCreateRenderPass
vkCreateRenderPass2KHR
vkCreateSampler
vkCreateSemaphore
vkCreateShaderModule
vkCreateSwapchainKHR
vkCreateWin32SurfaceKHR
vkCsChunk
vkCsChunkFlags
vkCsChunkPool
vkCsChunkRef
vkCsCmd
vkCsDataCmd
vkCsThread
vkCsTypedCmd
vkDataBuffer
vkDataSlice
vkDescriptorPool
vkDescriptorPoolTracker
vkDescriptorSlotMapping
vkDestroyBuffer
vkDestroyBufferView
vkDestroyCommandPool
vkDestroyCuFunctionNVX
vkDestroyCuModuleNVX
vkDestroyDescriptorPool
vkDestroyDescriptorSetLayout
vkDestroyDescriptorUpdateTemplate
vkDestroyDevice
vkDestroyEvent
vkDestroyFence
vkDestroyFramebuffer
vkDestroyImage
vkDestroyImageView
vkDestroyInstance
vkDestroyPipeline
vkDestroyPipelineCache
vkDestroyPipelineLayout
vkDestroyQueryPool
vkDestroyRenderPass
vkDestroySampler
vkDestroySemaphore
vkDestroyShaderModule
vkDestroySurfaceKHR
vkDestroySwapchainKHR
vkDevice
vkDeviceFeatures
vkDeviceFilter
vkDeviceInfo
vkDeviceMemory
vkDeviceWaitIdle
vkDsInfo
vkDsStencilOp
vkEndCommandBuffer
vkEnumerateDeviceExtensionProperties
vkEnumerateInstanceExtensionProperties
vkEnumerateInstanceLayerProperties
vkEnumeratePhysicalDevices
vkError
vkExt
vkFormatFlags
vkFramebuffer
vkFreeMemory
vkGetBufferDeviceAddressKHR
vkGetBufferMemoryRequirements
vkGetDeviceQueue
vkGetEventStatus
vkGetImageMemoryRequirements
vkGetImageSubresourceLayout
vkGetImageViewAddressNVX
vkGetImageViewHandleNVX
vkGetPhysicalDeviceFeatures2KHR
vkGetPhysicalDeviceFormatProperties
vkGetPhysicalDeviceImageFormatProperties
vkGetPhysicalDeviceMemoryProperties
vkGetPhysicalDeviceMemoryProperties2
vkGetPhysicalDeviceProperties
vkGetPhysicalDeviceProperties2KHR
vkGetPhysicalDeviceQueueFamilyProperties
vkGetPhysicalDeviceSurfaceCapabilitiesKHR
vkGetPhysicalDeviceSurfaceFormats2KHR
vkGetPhysicalDeviceSurfaceFormatsKHR
vkGetPhysicalDeviceSurfacePresentModes2EXT
vkGetPhysicalDeviceSurfacePresentModesKHR
vkGetPhysicalDeviceSurfaceSupportKHR
vkGetQueryPoolResults
vkGetSwapchainImagesKHR
vkGpuEvent
vkGpuEventHandle
vkGpuEventPool
vkGpuEventTracker
vkGpuQuery
vkGpuQueryAllocator
vkGpuQueryHandle
vkGpuQueryManager
vkGpuQueryPool
vkGpuQueryTracker
vkGpuVendor
vkGraphicsPipeline
vkGraphicsPipelineFlags
vkGraphicsPipelineInstance
vkGraphicsPipelineStateInfo
vkIaInfo
vkIlAttribute
vkIlBinding
vkIlInfo
vkImage
vkImageView
vkInstance
vkLifetimeTracker
vkMapMemory
vkMemory
vkMemoryAllocator
vkMemoryChunk
vkMetaBlitObjects
vkMetaBlitRenderPass
vkMetaClearObjects
vkMetaCopyObjects
vkMetaCopyRenderPass
vkMetaMipGenRenderPass
vkMetaPackObjects
vkMetaResolveObjects
vkMetaResolveRenderPass
vkMsInfo
vkNameSet
vkObjects
vkOmAttachmentBlend
vkOmAttachmentSwizzle
vkOmInfo
vkOptions
vkPipelineCache
vkPipelineLayout
vkPipelineManager
vkQueryData
vkQueuePresentKHR
vkQueueSubmission
vkQueueSubmit
vkRenderPass
vkRenderPassFormat
vkRenderPassOps
vkRenderPassPool
vkRenderTargets
vkResetCommandPool
vkResetDescriptorPool
vkResetEvent
vkResetFences
vkResetQueryPoolEXT
vkResource
vkRsInfo
vkSampler
vkShader
vkShaderConstData
vkShaderKey
vkShaderModule
vkShaderOptions
vkSignalTracker
vkSpecConstants
vkStagingDataAlloc
vkStatCounters
vkStateCache
vkSubmissionQueue
vkSwapchainBlitter
vkUnboundResources
vkUpdateDescriptorSets
vkUpdateDescriptorSetWithTemplate
vkWaitForFences
vkXrProvider
```

Obtained with this script:
```sh
grep -Poh "[^ x>]?vk[A-Z][^: -]+\("|grep -v  "Dxvk"|grep -o "[^(]*"|grep "^vk" |sort|uniq
```

# Portability (original README.md)

## gfx-portability
[![Build Status](https://github.com/gfx-rs/portability/workflows/Check/badge.svg?branch=master)](https://github.com/gfx-rs/portability/actions)
[![Matrix](https://img.shields.io/badge/Matrix-%23gfx%3Amatrix.org-blueviolet.svg)](https://matrix.to/#/#gfx:matrix.org)

This is a prototype library implementing [Vulkan Portability Initiative](https://www.khronos.org/blog/khronos-announces-the-vulkan-portability-initiative) using [gfx-hal](http://gfx-rs.github.io/2017/07/24/low-level.html). See gfx-rs [meta issue](https://github.com/gfx-rs/gfx/issues/1354) for backend limitations and further details.

Platform support:
- macOS/Metal (lib, icd)
- iOS/Metal (lib, icd)
- Windows/DX12 (lib, icd)
- UWP/DX12 (lib)

For those interested in performance, we did a comprehensive benchmarks of Dota2 and Dolphin Emulator on macOS. Results were published to gfx-rs blog [here](https://gfx-rs.github.io/2018/08/10/dota2-macos-performance.html) and [there](https://gfx-rs.github.io/2019/03/22/dolphin-macos-performance.html).

For the extension support, see `INSTANCE_EXTENSIONS` and `DEVICE_EXTENSIONS` in the code.

## Showcase

### [Dota2](https://github.com/ValveSoftware/Dota-2):
![Dota2](etc/dota2-river.jpg)

### Quake
- [vkQuake](https://github.com/Novum/vkQuake)
- [vkQuake2](https://github.com/kondrak/vkQuake2)
- [vkQuake3](https://github.com/suijingfeng/vkQuake3)

![VkQuake](etc/quake-main.jpg) ![VkQuake3](etc/quake3-main.jpg)

### [RPCS3](https://github.com/RPCS3/rpcs3):

![RPCS3-cube](etc/rpcs3-cube.jpg) ![RPCS3-scogger](etc/rpcs3-scogger.jpg)

### [Dolphin](https://github.com/dolphin-emu):
![Dolphin-sb](etc/dolphin-smash-bros.png) ![Dolphin-pm](etc/dolphin-paper-mario.png)
![Dolphin-mk](etc/dolphin-mario-kart.jpg) ![Dolphin-md](etc/dolphin-metroid.jpg)

## Instructions

Despite the fact it's written in Rust, the produced binaries have standard linking interface compatible with any program (written in the language of your choice). There are multiple ways to link to gfx-portability.

### Dynamic linking

Typically, you'd need to create a symbolic link with a name that a target application expects, e.g. `libvulkan.dylib -> libportability.dylib`.

Check out and build:
```
git clone --recursive https://github.com/gfx-rs/portability && cd portability
cargo build --manifest-path libportability/Cargo.toml --features <vulkan|dx12|metal>
```

### ICD provider

gfx-portability can be used with Vulkan loader like any other Vulkan driver. In order to use it this way, you need to build `libportability-icd` and point to it from an ICD json file:
```
VK_ICD_FILENAMES=portability/libportability-icd/portability-macos-debug.json <some_vulkan_app>
```

### Static linking

For C, you'd need to add `crate-type = ["cdylib"]` to `libportability-gfx/Cargo.toml` and build it with the backend of your choice. Note: features of this library are fully-qualified crate names, e.g. `features gfx-backend-metal`. For rust, just point the cargo dependency to `libportability-gfx`.

## Running Samples

### LunarG (API-Samples)
After building `portability` as shown above, grab a copy from https://github.com/LunarG/VulkanSamples.
Manually override the [`VULKAN_LOADER`](https://github.com/LunarG/VulkanSamples/blob/master/API-Samples/CMakeLists.txt#L189-L194) variable and set it to the portability library.
```
set (VULKAN_LOADER "path/to/portability/library")
```
Then proceed with the normal build instructions.

## Vulkan CTS coverage

Please visit [our wiki](https://github.com/gfx-rs/portability/wiki/Vulkan-CTS-status) for CTS hookup instructions. Once everything is set, you can generate the new results by calling `make cts` on Unix systems. When investigating a particular failure, it's handy to do `make cts debug=<test_name>`, which runs a single test under system debugger (gdb/lldb). For simply inspecting the log output, one can also do `make cts pick=<test_name>`.
