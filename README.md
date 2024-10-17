# TESSERAQT-N OS
or 4D-Qubes-Nexus-OS

N ise NixOS

A Reasonably Extra Secure Operating System

by NixOS and Qubes OS
--------------------------------------------------------------------------------------------------------------------------------------------------------------
4-dimensional Qubes OS fork. 3D = QubesOS . +1D = NixOS container structure. 4D = NixOSs in Qubes OS. 

  A Qubes OS fork symbolizing 4-dimensional cubes. The cubes symbolize virtual machines. NixOS can be installed on each cube. Thus, the container layer of NixOS is included in the cubes, changing the cubes from 3D to 4D. +1D = NixOS container structure. This creates 4D Qubes Nexus OS, which are four-dimensional cubes. Colloquially called TesseraQt OS, it is a project that aims to provide a secure and modular operating system structure by combining Qubes OS and NixOS. A reasonably extra secure operating system.  In this project, virtual machines in Qubes OS will run with NixOS by default; and dependencies and packages will be isolated within containers in this NixOS environment. Thanks to this structure, a 4-dimensional layered architecture will be created:
  1. Qubes OS - A split operating system for security.
  2. Virtual Machines (VMs) - Each isolated and running with NixOS.
  3. NixOS - Modular and reliable operating system running inside virtual machines.
  4. Containers - A structure within NixOS where dependencies and packages are run in isolation.

This architecture aims to maximize system security while offering significant improvements in modularity and manageability.

_____________________________________________________________________________________________________________________________________________________________
  TesseraQt stands for 4D Qube. We will create a multi-layered 4D operating system by adding QubesOS, which is 3D, and GNU Guix OS, which is 1D.  
Qubes OS aims to combine the highly secure Qubes technology (Xen Project based inter-VM interaction) with the Nix OS optimal data privacy container and NixPkgs Package Management System. By adding Nix containers, which are 1 Dimension, into the 3D Qube VMs, we will get a 4 Dimensional cube. This is how we will create Tesseract. 

  The reason why we claim that Qubes OS contains 3 dimensions: The Qubes OS Operating System carries a main operating system, fedora OS, thanks to Xen technology. This is the first dimension (later on the 1st dimension layer, the first dimension, will be replaced by NixOS by default). It also hosts all the drivers, packages and software needed for data privacy and security in separate virtual machines called Qubes.  This creates a two-dimensional security layer. Inside these virtual machines, programs, software, packages, drivers are installed. Anonymity can also be achieved by building a new virtual machine inside the desired virtual machine, for example by installing whonix and running tor browser on the tor network inside whonix.  This adds another layer of dimension and creates a three-dimensional structure. 

  According to our project, for data privacy and security, we will add isolated areas (containers) in Qubes (virtual machines) in the 3rd dimensional layer (and if desired in the first dimension, the main operating system layer) and enable applications, programs, software to be installed in containers. Containers within a Qube will be able to interact with each other through APIs. Also, the container and the virtual machine will interact with each other through APIs. Since Qubes can interact with each other thanks to the Qubes OS infrastructure, containers in different Qubes will also be able to interact with each other. We also chose Nix OS for security reasons: Nix OS will be installed inside the Qube VM in the 3rd dimension layer, isolated space for the 4th dimension layer - the container will be able to create containers easily thanks to Nix Pkgs. If desired, the host (1st dimension layer) OS can be installed as NixOS instead of Fedora. If desired, it can be continued with Fedora. But the new VMs will not run Fedora or Debian or any other Operating System. In Qubes, only Nix OS will run on VMs (with the exception of Whonix VM).   In this way, Extra Reasonably Secure level security will be provided.

-------------------------------------------------------------------------------------------------------------------------------------------------------------
Description: 

4D stands for Qubes OS, which I define as 3D, while layer 4, which is + 1 dimension, stands for NixOS, the Nix package management system and container structure. By adding one more dimension to Qubes OS we will get 4 dimensional cubes. In this way we will increase the Security Level.

Qubes indicates that the main operating system will be Qubes OS.

 The word “Nexus” means connection and union; the letter “N” in the word Nexus and the word “Nex” define NixOS. Nexus specifies that NixOS will run inside virtual machines in Qubes OS. 
 
- Nexus will also be the name of the distribution model, as Qubes OS will be our name if we join the Qubes OS project in the future. We will be distributed as a separate version called “Qubes OS Nexus”.
 
OS indicates that we are a reasonably ultra-secure operating system with a multi-layered security architecture.

- OS also stands for Optimally Shield. 

Optimally Shield's Meaning and Explanation:

    Optimal:
        The word “optimal” refers to the best or most efficient state. Since your project offers an architecture running NixOS operating systems in virtual machines, this name emphasizes to users that the system will provide the best performance and resource utilization.
        By taking advantage of the system's efficiency and flexibility, users will be able to manage their applications more effectively.

    Shield:
        The word “Shield” means protection and security. Since your project is combined with a security-oriented framework like Qubes OS, this term symbolizes the ability to protect users' data and systems from potential threats.
        “Shield” also represents the layers of protection and security measures provided by the software, which means that users are working in a secure environment.

Project Emphasis:

    Security and Efficiency: Optimaly Shield aims to provide users with a virtual environment that is both secure and efficient. The combination of NixOS and Qubes OS increases the resilience of the system by enhancing security, while at the same time ensuring optimal utilization of resources.

    Flexibility and Control: The project offers users a fourth dimensional structure, giving them the possibility to create independent containers in NixOS environments inside virtual machines. This allows users more flexibility when managing dependencies and packages.

    Community and Contribution: Optimaly Shield, with its open source philosophy, gives developers and users the opportunity to participate and contribute to the project. This allows for continuous development and improvement of the project. 

------------------------------------------------------------------------------------------------------------------------------------------

Project Objective

Using the secure and isolated virtual machine infrastructure offered by Qubes OS, we are unifying the modular building blocks of NixOS. Thanks to this project, every virtual machine will work with NixOS and thousands of dependencies and packages within each NixOS will be managed through containers.

This structure aims to increase system security, ease manageability and modular availability of packages. By combining the strong security architecture of Qubes OS with the dependency management capabilities of NixOS, cross-system harmonization will be achieved.

Layers of Architecture

  1. Qubes OS: Enhances security by providing complete isolation between the host system and virtual machines.
  2. NixOS VMs: Each virtual machine is powered by NixOS and managed independently.
  3. Containers: Within NixOS, dependencies, packages and services are isolated and controlled through containers.

Advantages

  1. Security The virtual machine isolation offered by Qubes OS maximizes the security of the system.
  2. Modularity: Thanks to the configurability of NixOS, virtual machines and their packages can be built in a completely flexible and modular structure.
  3. Isolated Dependencies: Containers ensure that dependencies are managed independently of each other and the integrity of the system is maintained.
  4. High Manageability: The modular configuration and declarative nature of NixOS makes system administration very easy.

Project Objectives

    Ensure NixOS is installed by default on Qubes OS virtual machines.
    Optimize package and dependency management through containers on NixOS.
    Provide multi-layered security and manageability by creating a secure and isolated architecture.
    Enabling different software environments to run independently on the same system.

How Can You Contribute?

If you would like to contribute to this project, please follow the steps below:

    Develop after forking the repository.
    Create pull requests to add new features or fix bugs.
    Share your feedback by opening an issue.

License

This project is licensed under the MIT license. See the LICENSE file for details.
