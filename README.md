# x86-CYOA

This repository contains my attempts and progress at creating a choose your own
adventure game entirely in x86 assembly. While the end goal of this is fairly
static, I have a few sub goals that I'd like to address as well:

- Keep all run-time code in x86 assembly - though other languages may be used
  for the build process and other utilities.
- Be able to flash the program onto a USB stick and boot from it.
- Keyboard input.
- Color output.

Some very tentative goals that may not be as easy to address:
- Allow users to save their progress
- A build system that takes a story (potentially in ChoiceScript?) and creates
  a bootable image for it.

I'm completely new to OS development and fairly new to assembly language in
general, but here's a list of things that I think will come in handy at one
point or another - the [`./doc`](./doc/) directory contains some more
information I've gathered and roughly organized.

- [wiki.osdev.org](https://wiki.osdev.org), particularly their [section on the BIOS](https://wiki.osdev.org/BIOS)
- [Ralf Brown's Interrupt List](https://www.cs.cmu.edu/~ralf/files.html)
  - [Interrupt Jump Table](https://www.ctyme.com/intr/int.htm) ([mirror](https://web.archive.org/web/20220727093910/https://www.ctyme.com/intr/int.htm)) -
    A more user-friendly way to browse the above interrupts.
