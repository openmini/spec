# spec

specifications for a quality mobile device

# explanation

the openmini spec mainly consists of a simple rule: if you can compile a program for an official implementation, you should be able to compile it for your custom implementation (with a few exceptions).

however, it has specific requirements for components like the screen, buttons, security features, and wireless support. these requirements specify improvements to user experience and reduce the barrier to entry for those using your implementation of openmini.

these specifications are described by the other files in this repository.

there are additionally varying levels of compatibility: stack, base, and pro - these correspond to the official devices with the same names. stack is a headless model intended for IoT applications, base is the original model with a standard (but somewhat limiting) feature set, and pro is a professional model with support for multitasking

conformance with a given specification implies conformance with the one before it, so a device conforming to the pro specification also conforms to the base specification, and a device conforming to the base specification conforms to the stack specification.
