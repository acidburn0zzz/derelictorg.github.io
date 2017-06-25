Derelict is a collection of dynamic bindings to C and C++ libraries for the D programming language. It enables users to access popular libraries such as OpenGL, SDL, Lua and more, easily and with little effort across several platforms. This set of documentation provides users with the necessary knowledge to get started with Derelict, including general information applicable to all packages in the collection and package-specific information for each package. It is recommended that new Derelict users read the general documentation first, followed by the specific documentation for packages they intend to use.

All Derelict packages make use of the same build and package management system, [DUB], and a common foundation in the form of DerelictUtil. The sections of this documentation that are not package-specific outline the common steps required to configure a project to build and link with Derelict packages, as well as the common interface used to use the Derelict packages in code.

While the steps to use most Derelict packages are identical, there are sometimes exceptions to the rule. Furthermore, each package has its own versioning scheme independent of the C or C++ library to which it binds. Because of this, before implementing Derelict in a project, it is advised to take the time to read the specific documentation for any packages the project makes use of. This will ensure the project is based on the version of the package appropriate to its requirements and any special steps the package requires can be understood.
        
[DUB]: http://code.dlang.org/download