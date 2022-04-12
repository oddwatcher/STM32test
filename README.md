# STM32test
a few test around stm32s
##To Do
this will hold a platform like program hosting a flight controller

The Goal of this project is to establish a drone flying or walking or drowning config it to whatever you like as the cpu/s still have the ability to handle the code.

the code will be in approx five stages:

## Sensoring : 

acquires raw data from hardware specifc codes;

## Adjustment : 

convert the data to human-friendly(or computer  friendly);

## Applications : 

PIDs and other things you may like ,the goal is to code as you do like over a x86 machine,think less about the IOs use pointers to transport the data,apps runs in a row;

## Channeling(mixing) : 

mix the outputs according to privillage or flitering;

## Output : 

Hardware specifc output like serial write or PWM output.

Stages runs in a loop and you may apply some hardware specific interrupts to it which currently not in consideration.



