# spot-welder-timer-stm32
battery and thin sheet metal spot welder timer with stm32f103c8 microcontroller and solid state relay module

needs

1.. a modified transformer with output capability more than 700 watts in power.  low voltage output side should be 4-5 volts and have thick wire coil windings up to 16mm2  copper conductor cross sectional area. i use a 900 watts microwave owen transformer have original primary windings and 4 turns 16mm2 
copper windings. 

2.. an optocoupler isolated solid state relay module. i use 80 amps zenli soft switching solid state relay. 

3. a stm32f103c8t6 blue pill microcontroller board.

4. a nokia 5110lcd screen

5. two buttons one foot pedal and one parameter setting push button, jumper wires for blue pill

6. spot welding pen tool with push button.


7. a good 5vdc micro usb up to 1 amp dc mobile phone charger for supplying stm32
   
8. power grid cable for primary side and solid state switching. 

main.h gpio.c have showing nokia lcd pins.

A2 for increasing transformer pulse count

A8 output of timer one pulse timer to solid state relay opto led.

A9 is timer trigger pin for making pulses.

mot have 20 watts 20joules of energy pump for every 20ms time.

if you need to melt a spot weld area you can calculate energy and test for correct parameters. record parameters to your paper list and use.

i can spot weld 18650 batteries with 0.2mm nickel shhets 80ms+ pulses 

you can change nokia screen with 2x16 character lcd. with its libraries if you want.

all project files in zip file.
