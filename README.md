What is this?
=============

This is a recording of various recordings I've gathered from various people's
laptops using ps2emu-record. All of these recordings have been done with stable
versions of ps2emu-record, although they are from varying distributions and
kernel verions.

Replaying these recordings
==========================

Of course, all of these recordings can be played back with ps2emu-replay. The
real challenge comes with getting the right kernel version down. The way PS/2
drivers interact with the devices can change between kernel versions, and as a
result recordings made on different kernel versions then the host machine that
is attempting to play said recordings may not always work. For best results, try
to have a matching kernel to the one which the recording was done on. All of the
recordings have the kernel information at the header of the text file.

Organization
============

All of the recordings seen here are organized in the following fashion:

``
Manufacturer/Model/Kernel version.txt
``

In situations where the kernel the recording was done on was most likely not a
stock kernel (for example, a downstream Ubuntu kernel), I've made note of the
distribution with a little note such as "-Ubuntu" at the end of the text file.
