# Device-tree
IMportant Question http://www.thegeekstuff.com/2012/08/c-interview-questions/?utm_source=feedburner
While learning device tree I found below links very useful 
  1). https://stackoverflow.com/questions/22901282/hard-time-in-understanding-module-device-tableusb-id-table-usage
  2). https://stackoverflow.com/questions/22777644/detect-the-presence-of-a-device-when-its-hot-plugged-in-linux/22777951#22777951
   At link 2, there will be 2 link 
   
   
   Very useful link it has all chapter <<learned Interrupt form this >>
  https://notes.shichao.io/lkd/ch7/#interrupts
  
  
  Copy from user , why we should use ?  very usefull link
  http://linuxforthenew.blogspot.in/2013/01/why-doshould-we-use-copyfromuser-or.html
  So copy_to_user and copy_from_user provide protection, first it provides protection ensuring the address is a valid user space address and handling the page fault in case of invalid pointer sending EFAULT to user rather than crashing the kernel.
For exact details, please refer the documentation in the linux kernel how this is handled, please refer https://www.kernel.org/doc/Docum...
  
  I2c Releated topics 
  link https://www.i2c-bus.org/clock-stretching/
  
  INterrupt
  Link : https://stackoverflow.com/questions/5934402/can-an-interrupt-handler-be-preempted
  some interrupt handlers (known in Linux as fast interrupt handlers) run with all interrupts on the local processor disabled. This is done to ensure that the interrupt handler runs without interruption, as quickly as possible. More so, all interrupt handlers run with their current interrupt line disabled on all processors. This ensures that two interrupt handlers for the same interrupt line do not run concurrently. It also prevents device driver writers from having to handle recursive interrupts, which complicate programming
  
  DMA 
  http://www.makelinux.net/ldd3/chp-15-sect-4
