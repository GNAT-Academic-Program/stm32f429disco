# stm32f429disco

**Alire Board Support Package for the stm32f429disco dev board**

### Note ###
This package is a dependency, a library. Usually, you create an application building upon this crate.
Look at the [stm32_blinky_demo](https://github.com/GNAT-Academic-Program/stm32_blinky_demo) for such an example.

### Prerequisite (instructions tested on Linux Ubuntu 20.04 only)

- [Alire](https://github.com/alire-project/alire/releases) the Ada package manager.

### [Instructions to Use](https://github.com/GNAT-Academic-Program#install-alire-an-ada-package-manager) ###


# STM32F429DISCO Board Support Package

This repository contains the Alire Board Support Package (BSP) for the STM32F429DISCO development board. It is designed to provide the foundational components necessary to develop Ada applications on this specific hardware platform.

## Overview

The `stm32f429disco` BSP offers a comprehensive starting point for your embedded projects on the STM32F429DISCO board, simplifying the hardware abstraction layer. It ensures seamless integration with the Ada ecosystem, leveraging [Alire](https://github.com/alire-project/alire), the Ada package manager, for dependency management and project configuration.

## Getting Started

### Prerequisites

Ensure you have the following prerequisites installed and set up on your system. The instructions are verified for Linux Ubuntu 20.04:

- **Alire**: The Ada package manager is essential for managing dependencies and project configuration. Download and install Alire from the [official releases page](https://github.com/alire-project/alire/releases).

### Installation and Usage

1. **Install Alire**: Follow the [installation instructions](https://github.com/GNAT-Academic-Program#install-alire-an-ada-package-manager) for Alire to set up the Ada package manager on your system.

2. **Clone the Repository**: Clone this BSP repository to your local machine to start working with the STM32F429DISCO board.

    ```bash
    git clone https://github.com/your-username/stm32f429disco.git
    cd stm32f429disco
    ```

3. **Use with Your Project**: This BSP is typically used as a dependency in your own application projects. Refer to the [stm32_blinky_demo](https://github.com/GNAT-Academic-Program/stm32_blinky_demo) for an example of how to build an application upon this crate.

    In your project's `alire.toml`, add `stm32f429disco` as a dependency to seamlessly integrate the BSP into your workflow.

### Contributing

Your contributions are welcome! If you wish to improve or extend the capabilities of this BSP, please feel free to fork the repository, make your changes, and submit a pull request.

## Support and Community

If you encounter any issues or have questions regarding the usage of this BSP, please file an issue on the GitHub repository. For broader discussions or to seek assistance, join the Ada developer community on platforms like [Ada Discourse](https://discourse.ada-lang.org).

---

Happy Coding with Ada and the STM32F429DISCO board!
