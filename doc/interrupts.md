# Useful Interrupts
Interrupts that may come in handy, in no particular order. Unless otherwise
specified, numbers are *probably* in hexadecimal.

I'm not really sure how to organize this page. Maybe it'll be reorganized by use
case later on?

## INT 0x15
- [WAIT](https://web.archive.org/web/20200924153353/http://www.ctyme.com/intr/rb-1525.htm), AH = 0x86h, CX:DX = interval in microseconds

## INT 0x10
- [SET VIDEO MODE](https://web.archive.org/web/20200821053156/http://www.ctyme.com/intr/rb-0069.htm), AH = 00h, AL = video mode (maybe 0x07h for 80x25 chars?)
