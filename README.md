# leap42.3-rr2680-module

Grab the fixed sources from uberDoward and fix the kernel-check:

Inside os_linux.c
#if LINUX_VERSION_CODE >= KERNEL_VERSION(4,8,0)

change to

#if LINUX_VERSION_CODE >= KERNEL_VERSION(4,4,0)
  
BINGO!
