# Fungesector

This is the source code for the Fungesector, a Befunge-93 interpreter written in 8086 assembly.

Made for the RC2024/10

Build instructions for Linux

1) To create a floppy image, execute this command inside the project:

`fasm -d FLOPPY=1 program.x86 Sector.img`

2) To run in QEMU, execute this command:

`qemu-system-i386 -drive format=raw,file=Sector.img`
