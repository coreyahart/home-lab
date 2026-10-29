# 01: Domain Controller VM Setup

## Goal
Build the virtual machine that will become the domain controller for my home lab.

## Host Environment
- Host RAM: 32 GB
- Virtualization: enabled (images/DC01-host-specs.png)
- Software: VirtualBox(7.2.22), Windows Server 2022 ISO

## VM Configuration
- Name: DC01
- RAM: 4 GB
- CPUs: 2
- Disk: 50 GB
- Adapter 1: Internal Network (labnet), private lab network (images/DC01-network-adapter-1.png)
- Adapter 2: NAT, internet access for updates and activation (images/DC01-network-adapter-2.png)

## Windows Server install
- Edition: Standard Evaluation (Desktop Experience)
- 180-day evaluation

## Guest Additions
- Installed a guest addition to be able to bridge the gap between my host device to the virtual device. (Being able to use clipboard from Host to Virtual Machine)

## Snapshot
- Created "Fresh Install" snapshot (images/DC01-first-snapshot.png)

## Problems and Fixes
- No problems in this stage.

## What I've Learned
- I've learned how to configure a VM to be ready to be a usable Domain Controller.


