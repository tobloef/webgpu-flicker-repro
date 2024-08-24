Expected output:

![image](https://github.com/user-attachments/assets/cb929d39-d398-49ff-b339-1b3a6bc28447)

* (https://tobloef.com/webgpu-flicker-repro/no-check)[No depth check] (Expectedly incorrect, sorted wrong)
* (https://tobloef.com/webgpu-flicker-repro/once)[Custom depth buffer (once)] (Unexpectedly incorrect, has artifacts)
* (https://tobloef.com/webgpu-flicker-repro/continous)[Custom depth buffer (continuous)] (Unexpectedly incorrect, has artifacts)
* (https://tobloef.com/webgpu-flicker-repro/builtin)[Built-in depth buffer] (Correct, but I'm trying to do it _without_ the built-in depth stencil)
