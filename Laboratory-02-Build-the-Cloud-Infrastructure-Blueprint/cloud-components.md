# Cloud Infrastructure Components

## 1. Compute Resources

### Example in the KillerCoda Environment

The CPU and RAM available on the Linux server are examples of compute resources.

### Purpose

Compute resources provide the processing power and memory needed to run applications, services, commands, and operating system processes.

### Importance in Cloud Computing

Compute resources are important because applications need processing power and memory to operate. Cloud providers allow organizations to increase or decrease computing resources depending on their workload.

### Relation to KillerCoda

The KillerCoda environment provides a virtual Linux server with an Intel Xeon CPU and 1 CPU core, along with 1.9 GiB of RAM. These resources allow the server to execute Linux commands and run applications.

---

## 2. Storage Resources

### Example in the KillerCoda Environment

The 19 GB virtual disk and mounted file systems are examples of storage resources.

### Purpose

Storage resources are used to store the operating system, applications, configuration files, logs, and other data.

### Importance in Cloud Computing

Cloud storage allows organizations to store and access data without needing to maintain physical storage hardware themselves. Storage resources can also be managed and expanded according to an organization's needs.

### Relation to KillerCoda

The KillerCoda Linux server uses a virtual disk with a main 19 GB file system mounted at `/dev/vda1`. The server also has mounted file systems such as `/boot` and `/boot/efi`.

---

## 3. Networking Resources

### Example in the KillerCoda Environment

The server's network interface and IP address are examples of networking resources.

### Purpose

Networking resources allow the Linux server to communicate with other computers, applications, and services.

### Importance in Cloud Computing

Networking is important because cloud resources need to communicate with users, applications, databases, and other services. Cloud networking also provides connectivity, routing, and security.

### Relation to KillerCoda

The KillerCoda server has an assigned IP address that allows it to communicate through the network. The `hostname -I` command was used to identify the server's IP address.

---

## 4. Operating System

### Example in the KillerCoda Environment

Ubuntu Linux is the operating system used by the KillerCoda server.

### Purpose

The operating system manages the computer's resources and provides the environment where applications and services can run.

### Importance in Cloud Computing

An operating system is an important part of cloud computing because virtual machines and cloud servers need an operating system to run applications and manage system resources.

### Relation to KillerCoda

The KillerCoda environment provides an Ubuntu Linux server. Linux commands such as `uname -r`, `lsb_release -a`, `free -h`, and `df -h` were used to inspect the system.
