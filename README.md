# stm32f401_advance_debug_SWO
stm32f401cc advance debug with SWO trace 

Sometime a few weeks ago, my official ST-LINK V2 stops working with my boards (like WeAct 3.0). So I think the boards use clone stm32f401 chips. 
So I bought a ST-LINK V2 clone from Aliexpress. it has a Geehy AMP32F103CBT6 chip inside which is a exact clone of STM32F103CBT6.
I wired the PA10 pin(with a 100ohm resistor), then connect to the SWO(PB3) pin of a target STM32F401 chip(It is also a clone chip)
on WeAct 3.0 board. It works with SWO trace debug function.---5/22/2022
