Platform: NUCLEO STM32L412KB    

Pushbutton debouncing with 4 buttons on PB0, PB1, PB4 an PB5 (int. pull-up) generate an Interrupt with falling edge and toggle the green board LED on PB3. 
The function "void SysTick_Handler(void)" was cutted from file stm32l4xx_it.c and inserted in main.c. 
This function was called every ms and herein a keystroke is evaluated within this function.