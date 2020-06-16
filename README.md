# Compressed_Static_Kube_C


## LDD for this .so:
ldd ./kubernetes/build/libkubernetes.so 
	linux-vdso.so.1 (0x00007ffd815bb000)
	libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007f629cd15000)
	/lib64/ld-linux-x86-64.so.2 (0x00007f629d2bf000)
  
## For build instructions, please refer to official client.

## Additions:
* Static libraries -> libcurl and libyaml.
* Changes in Cmake to not search for curl 7.58 and build using static compiled libs.
