# VoidHeart
VoidHeart — A Linux Kernel Module that intercepts mount, rename, and unlink syscalls to prevent from doing this shit, destruction, and change. Inspired by a heart that refuses to forget working lkm for versions like 4.x linux kernels :)

# DETAILS

I have used return -EPERM to genreate errors like permission denied blocking further access to it in my hook easy 
blocked execution of:
1.mount syscall — blocks mounting of filesystems

2.rename syscall — blocks renaming or moving files

3.unlink syscall — blocks deleting/removing files

4.unlinkat syscall — blocks deleting files relative to a directory file descriptor

Maded for fun :) 
