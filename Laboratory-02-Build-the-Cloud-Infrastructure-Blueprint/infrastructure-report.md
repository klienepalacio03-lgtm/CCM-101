# Cloud Infrastructure Assessment Report

## 1. Operating System

**Operating System:** Ubuntu

The cloud server is running Ubuntu Linux. The operating system provides the environment needed to run applications, manage files, control system resources, and perform administrative tasks.

## 2. Kernel Version

**Kernel Version:** 6.8.0-136-generic

The Linux kernel manages important system resources such as the CPU, memory, storage, devices, and networking.

## 3. CPU

**CPU Model:** Intel Xeon E312xx (Sandy Bridge, IBRS update)

**Number of CPU Cores:** 1

The CPU provides the processing power needed to execute applications, commands, and system processes on the cloud server.

## 4. Total RAM

**Total RAM:** 1.9 GiB

RAM provides temporary memory for the operating system and applications running on the server.

## 5. Disk Capacity

**Disk Capacity:** 19 GB

The main disk is mounted at `/` and is provided by `/dev/vda1`. It is formatted using the ext4 file system.

## 6. Mounted File Systems

The Linux server contains several mounted file systems:

| Mount Point | Source | File System |
|---|---|---|
| `/` | `/dev/vda1` | ext4 |
| `/boot` | `/dev/vda16` | ext4 |
| `/boot/efi` | `/dev/vda15` | vfat |
| `/sys` | sysfs | sysfs |
| `/proc` | proc | proc |
| `/dev` | udev | devtmpfs |
| `/run` | tmpfs | tmpfs |

Mounted file systems allow the operating system to access storage devices and virtual file systems through specific directories.

## 7. Hostname

**Hostname:** ubuntu

The hostname identifies the Linux server on the network and helps distinguish it from other systems.

## 8. IP Address

**IP Address:** `172.30.1.2 172.17.0.1`

The IP address allows the cloud server to communicate with other devices and services through the network.

## 9. Investigation Summary

The KillerCoda environment provides a practical example of a cloud-based Linux server. The investigation showed that the server has compute resources such as a CPU and RAM, storage resources such as a virtual disk, networking resources such as an IP address, and an operating system that manages the environment.

The investigation also demonstrated how Linux commands can be used to identify important infrastructure information before designing or deploying a cloud architecture.

## 10. Screenshots

Screenshots of the Linux investigation will be stored in the `screenshots` folder.
