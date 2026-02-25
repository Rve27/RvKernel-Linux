# RvKernel-Linux
RvKernel Linux is a custom Linux kernel, a fork of [CachyOS](https://github.com/CachyOS/linux-cachyos) kernel

### Available Schedulers
| Scheduler | Full Name | Package(s) | Best for... | Developer |
| :--- | :--- | :--- | :--- | :--- |
| **[BORE](https://github.com/firelzrd/bore-scheduler)** | **B**urst-**O**riented **R**esponse **E**nhancer | `linux-rvkernel-bore` | Interactive workloads & gaming | [firelzrd](https://github.com/firelzrd) |
| **[EEVDF](https://lwn.net/Articles/927530/)** | **E**arliest **E**ligible **V**irtual **D**eadline **F**irst | `linux-rvkernel-eevdf` | General-purpose computing | Peter Zijlstra |

### Installation
- Install the kernel
```yay -S linux-rvkernel-bore-clang```
or
```yay -S linux-rvkernel-bore-gcc```
---------------------------------------
- Install the headers (optional)
```yay -S linux-rvkernel-bore-headers-clang```
or
```yay -S linux-rvkernel-bore-headers-gcc```
---------------------------------------
- Install the NVIDIA driver (optional)
```yay -S linux-rvkernel-bore-nvidia-open-clang```
or
```yay -S linux-rvkernel-bore-nvidia-open-gcc```
---------------------------------------
- Install the LFS driver (optional)
```yay -S linux-rvkernel-bore-lfs-clang```
or
```yay -S linux-rvkernel-bore-lfs-gcc```