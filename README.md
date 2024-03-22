# spec

specifications for a quality mobile device

# explanation

the openmini spec mainly consists of a simple rule: if you can compile a program for the base implementation, you should be able to compile it for your custom implementation (with a few exceptions).

however, it has specific requirements for components like the screen, buttons, security features, and wireless support.

these specifications are described by the other files in this repository.

the exceptions mainly pertain to features which aren't really necessary (due to their limited use). this includes things like hardware random numbers, cryptographic accelerators, and 802.15.4 support. these exceptions are explained in further detail by the files describing those related requirements.
