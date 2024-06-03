be on linux have a rust installation with  pkg-config fuse3
create a folder for the program to run  ex temp
```
cargo build && cargo run &  cd temp
```


# FileSystem / fs / kernel module

- [Python FUSE Filesystem by Stavros](https://www.stavros.io/posts/python-fuse-filesystem/)
  A detailed guide on creating a filesystem in Python using the FUSE library.

- [ACM Paper on Filesystem](https://dl.acm.org/doi/pdf/10.1145/3494556)
  An academic paper discussing recent advancements and research in filesystem technology.

- [Filesystem Chapter from Inria](https://inria.hal.science/hal-03440824/file/497034_1_En_26_Chapter.pdf)
  A comprehensive chapter on filesystems from an Inria publication, providing in-depth technical insights.

- [Hello World Kernel Module by Ccarral](https://ccarral.github.io/en/projects/hello_world_kernel_module/)
  A beginner-friendly tutorial on writing a simple "Hello World" kernel module.

- [OSXFUSE Filesystems](https://github.com/osxfuse/filesystems/tree/master)
  The official repository for OSXFUSE filesystems, featuring various implementations and examples.

- [FUSE Tutorial by Pfeiffer](https://www.cs.nmsu.edu/~pfeiffer/fuse-tutorial/?source=post_page-----ee8f90fd0a2f--------------------------------)
  A step-by-step tutorial on creating filesystems using the FUSE library, aimed at beginners.

- [Hackaday on Linux FUSE](https://hackaday.com/2021/08/31/linux-fu-user-space-file-systems-now-for-windows-too/)
  An article exploring the use of user-space filesystems in Linux and their availability on Windows.

- [Writing a Simple Filesystem Using FUSE](https://www.maastaar.net/fuse/linux/filesystem/c/2016/05/21/writing-a-simple-filesystem-using-fuse/)
  A practical guide to writing a simple filesystem using the FUSE library in C.

- [Linux VFS Documentation](https://dri.freedesktop.org/docs/drm/filesystems/vfs.html)
  Official documentation for the Virtual Filesystem (VFS) in the Linux kernel, covering its structure and usage.

- [Old Blog about Filesystem on LWN](https://lwn.net/Articles/13325/)
  An older blog post discussing filesystems, providing historical context and foundational knowledge.

- [Filesystem Code Sample on LWN](https://lwn.net/Articles/13379/)
  A blog post featuring sample code for filesystem operations, useful for learning through examples.

- [OSX-KVM on GitHub](https://github.com/kholia/OSX-KVM)
  A GitHub repository with resources and tools for running macOS on KVM, including filesystem-related components.

- [Apple Developer VFS Documentation](https://developer.apple.com/documentation/kernel/vfs)
  Apple's official documentation on the Virtual Filesystem (VFS) for macOS, detailing its architecture and API.

- [Updated Code Version Gist](https://gist.github.com/RadNi/9d8a074e6264c1664b97b8eee11b1d2a)
  A Gist containing updated versions of code samples for filesystem projects.

- [Kernel Modules Drivers Lecture by Haifux](http://www.haifux.org/lectures/86-sil/kernel-modules-drivers/kernel-modules-drivers.html)
  A lecture on kernel modules and drivers, providing foundational knowledge and practical examples.

- [Seccomp by Litchipi](https://litchipi.site/post/7320799171169331056)
  An article discussing Seccomp, a Linux kernel feature for restricting the system calls a process can make.

- [ZboxFS on GitHub](https://github.com/zboxfs/zbox)
  The official repository for ZboxFS, a high-level library for building secure, user-space filesystems in Rust.
  - [inode](https://en.wikipedia.org/wiki/Inode)
   a directory entry contains only a name for the associated file and a pointer to the file itself. This pointer is an integer called the i-number (for index number) of the file. When the file is accessed, its i-number is used as an index into a system table (the i-list) stored in a known part of the device on which the directory resides. The entry found thereby (the file's i-node) contains the description of the file.

  - (WARNING) the list of links was hand choosed the description was written by a ai but reviewed by a human(me)
