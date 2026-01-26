# Viento OS

🌀 A light, fast and minimalist hobby operating system.

#How to boot?

"qemu-system-x86_64 \
  -kernel bzImage \
  -initrd init.cpio \
  -append "root=/dev/ram rdinit=/init console=ttyS0 console=tty0"

"
