# What is OptionBSD?
OptionBSD is a project based on FreeBSD.
It already features a beautiful UI, ecosystem synchronization, drivers, and APIs for developers, with a user-friendly and unique UX.

# Latet build
OptionBSD 0.0.1 is a test build in development, aimed at developers. It features a minimal system that is not yet a final version for general use. This release includes an application manager, ecosystem synchronization, and improved security.

# About applications
Applications in OptionBSD are important elements, and a package format called "opa" was developed for their implementation. A utility called **opman** was created for its installation. Usage of **opman**:

- `opman install /path/to/app.opa` – install an application from a file
- `opman remove com.app.id` – remove an application by App ID

# Application development
Clone `optionbsd/voltera` and add `voltera/bin` folder to path (only for UNIX/Unix-like)

- `vproj ~/ProjectFolder` - creating new project in your home directory
- `voltera ~/ProjectFolder` - building project to `.opa` file
