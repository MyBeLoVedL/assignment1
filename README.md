# main page



> This is a personal repo for assignment one 
>
> 21180330 		lipan  		class  24



all right,let's talk about something ~~interesting~~,



## OS 



what is an OS ? 

OS actually is just a gigantic C program,provide services via **system call** to user program : *process* ,and manage hardware resources. Three most important parts lie there.

* Virtualization 
* Concurrency
* Persistence



Here is a code snippet from an mini OS developed by MIT : **XV6** , define the structure of superblock. 



``` c
struct superblock {
  uint magic;      // Must be FSMAGIC
  uint size;       // Size of file system image (blocks)
  uint nblocks;    // Number of data blocks
  uint ninodes;    // Number of inodes.
  uint nlog;       // Number of log blocks
  uint logstart;   // Block number of first log block
  uint inodestart; // Block number of first inode block
  uint bmapstart;  // Block number of first free map block
};
```



![img](view.jpg)



[clike me](sample.md)

