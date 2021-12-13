simpleOS
-----

Features: 
- Memory paging
- i8259 PIC interrupt handling
- Exception handling
- Keyboard input buffer
- In memory read-only filesystem
- Round-robin scheduling based on Programmable Interrupt Timer

How to run
-----
If using latest QEMU:

qemu-system-i386 -hda "student-distrib/mp3.img" -m 512 -name test -gdb tcp:127.0.0.1:1234 -soundhw pcspk -soundhw sb16 -serial /dev/ttyUSB0
