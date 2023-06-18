# numa.h

The error message you received indicates that the compiler cannot find the header file numa.h while compiling the file eal_memory.c in the librte_eal/linux directory of the DPDK library. The numa.h header file is related to NUMA (Non-Uniform Memory Access) support in Linux.

To resolve this issue, you need to ensure that the necessary development package for NUMA is installed on your system. The package name may vary depending on your Linux distribution, but you can try the following steps:

Update package lists: Run the following command to update the package lists on your system:

```
sudo apt update
```

Install NUMA development package: Use the package manager to install the development package for NUMA. On Debian-based systems, you can use the following command:

```
sudo apt install libnuma-dev
```
