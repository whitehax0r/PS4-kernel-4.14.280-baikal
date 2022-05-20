This is a vanilla kernel 4.14.280 (2022-05-18) with PS4 patches+baikal patches.

This kernel works on ps4 baikal southbridge. Not tested on belize or aeolia yet.

git clone https://github.com/whitehax0r/PS4-kernel-4.14.280-baikal.git

>cd PS4-kernel-4.14.280-baikal

>mv config .config

>make -j7

Linux kernel
============

There are several guides for kernel developers and users. These guides can
be rendered in a number of formats, like HTML and PDF. Please read
Documentation/admin-guide/README.rst first.

In order to build the documentation, use ``make htmldocs`` or
``make pdfdocs``.  The formatted documentation can also be read online at:

    https://www.kernel.org/doc/html/latest/

There are various text files in the Documentation/ subdirectory,
several of them using the Restructured Text markup notation.

Please read the Documentation/process/changes.rst file, as it contains the
requirements for building and running the kernel, and information about
the problems which may result by upgrading your kernel.
