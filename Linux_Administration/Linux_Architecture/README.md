# Linux Architecture and Basics of Linux:

## Linux
- It is a **monolithic kernel** which is used to empower operating systems like ubuntu, redhat, debian, suse etc.
- developed by Linux Trovalds.
- C programming is used for developing the kernel.

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/7aa6ad02-111e-44b4-bd95-8061c3a4c613" />

## Features of Linux kernel:
- Open-source
- Light weight
- Managed updates
- Multi tasking
- Multi User Support
- Security
- CLI Based

## Linux Architecture:

<img width="589" height="589" alt="image" src="https://github.com/user-attachments/assets/99b1420c-2ee0-41ce-85ff-57fa8a337605" />

## Kernel:

- It is the heart of the operating system.
- It is lies between shell and hardware and responsible for managing system calls.
- It uniquely identifies each hardware components and instruct hardware to perform operations.
- It also provides API for the application to communicate with hardware components and other applications

## Functions of kernel:
- Process scheduling & Management 
- Resource Allocation
- Memory management
- Device management 
- Security
- Application interaction
  
## Monolithic Kernel:
- It is a type of kernel in which all the operating system and the process running on the operating system shares same memory address.
- It appears to the RAM as single process is running by utilising the memory.
- It is faster than micro kernel which is used operating systems like windows and react os.

## Shell:
- It acts as interface between the user and kernel.
- It get instructions from the use and pass it to kernel to perform task.
- there are various types of shell in linux.

### Bourne Shell:
- It is the first shell developed for linux.
- Succeeded by BASH shell.
- It is developed by GNU to support open-source project like linux.
- Path of the bourne shell is #!/bin/sh

### C Shell:
- It uses the C programming language to interact with kernel.
- Path of the C shell is #!/bin/csh

### Korn Shell:
- It combines the feature of both bourne shell and c shell
- Path of the korn shell is #!/bin/ksh

### Bourne Again Shell:
- It is the default shell in most of the linux based OS.
- It has advanced features like command line history, auto complete and scripting.
- Path of the bash shell is #!/bin/bash

### Z Shell:
- It is an advanced shell which has features like autocorrection, command completion, customization of themes etc.
- Path of the z shell is #!/bin/zsh

### T Shell:
- It is an advanced version of C shell with features like command history, command completion.
- Path of the T shell is #!/bin/tsh
- Not installed by default.

## Hardware layer:
- It is the lowest layer of the architecture which composed of harware components and its drivers

### System utility:
- It is a command line utility used to perform administrative task

### Application layer:
- It composed applications and programs installed by the user

