# stm32f1_delay

>> Thanks **Mr.Yohanes Erwin Setiawan** for his *SysTick-interrupt-based delay library*.

>> Thanks my lecturers **Mr.Ha Huynh** and **Mr.Hoan Phan** for their supporting.

Idea : This delay library is no use systick interrupt, just counts the clock.

Purpose : Use this library if you don't want to be in trouble with NVIC priorities (the easiest way). Or you can try relocating the interrupt vector table to make the SysTick interrupt works with NVIC.
  
 Use ``DelayUs(us)`` to delay in microseconds.
 
 Use ``DelayMs(ms)`` to delay in miliseconds.
