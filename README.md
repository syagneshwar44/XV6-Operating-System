# XV6-Operating-System
Qemu allocates 128Mb of memory. And every memory page is 4096 bytes. So there’s 4096 * 32734 = 134078464 bytes of memory left. It’s close to 128 Mb and close to our expectation because there are no processes running. The user program output shows fewer memory pages because the init process has been created, and memory page has been allocated.
