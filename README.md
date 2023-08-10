# Vetcon_Badge_2023

A short lesson in not fucking up your badge.

> [!WARNING]
> I know it looks super fun, but don't put the unsoldered male and female headers together, they are very tight fitting and you may not get them apart. Even if you are a Marine and you think it will be really funny to put it in and out while giggling, please don't. Or do. Consider yourself warned.

The first thing you will see is a bag:

![Bagged](https://github.com/wery67564/Vetcon_Badge_2023/assets/22899183/c3c61296-8754-4d65-88a8-0088fc1e183f)

This is your badge, you will need to do a little assembly to have it be complete. Once complete you will have one SAO Totem and 6 SAOs.

This assembly will require some basic through-hole soldering. This guide will not give you instructions on how to solder,  but this one will:

https://learn.sparkfun.com/tutorials/how-to-solder-through-hole-soldering/all


The first step is to gently unbag your badge. Some of the components are taped to PCBs, so be gentle to make your life easier down the road. This is what you should have:

![Neat](https://github.com/wery67564/Vetcon_Badge_2023/assets/22899183/9e6e8a6e-948d-4da6-ab8b-23dab952182c)

The components with links to their supply source will be at the end of this guide. If you are missing anything please reach out to the Vetcon booth.

The order of soldering these together is not critical, but if you solder together the totem (crayon box) first, you may avoid putting the wrong headers on. 

#Totem

The (5) female headers go on the totem. The (6) male headers go on the crayons. You can do whatever you want, but this method will ensure maximum SAO compatibility. 

> [!WARNING]
> Make sure the female headers are oriented correctly. The silkscreen shows the orientation of the "key" and it should be oriented so the keys are "pointing up" The below picture demonstrates this.

 ![Front Totem Completed](https://github.com/wery67564/Vetcon_Badge_2023/assets/22899183/f88f9e46-9fac-4d7b-9fdf-efcaed8e7619)

It is recommended that you solder the headers before the battery pack on the back. It is also recommended that you solder all 6 pins on each header for maximum strength. As mentioned earlier, the fit of the male and female headers is tight, and if the full complement of pins is soldered, it will reduce the chance of breaking a solder joint.

Next, solder the battery pack onto the back of the totem pay attention to which pad is positive and which is negative. The included battery pack has a red wire to denote positive and a black wire to denote negative.

For aesthetic reasons you can trim the wires so as to not have excess, however, you can also just wrap the wires around the battery pack or let them flop out, it is only an aesthetic difference.

> [!WARNING]
> The included battery pack is 2x AA batteries, depending on the type of AA battery you use it will produce between 2.4v to 3v. Some SAOs, particularly those with ESP32, Bluetooth/wifi, or the breathalyzer, require 3.3v. There are no constraints that prevent attaching a different battery pack of your choosing so as to have wider SAO compatibility.

#Crayons

The crayon SAOs have three components for each, an LED, a resistor, and a male header. I recommend soldering the header last, but the order is not important. 

4 of the crayons should have the  resistor and LED for that crayon taped to them. Should.

The resistor and LED loose in the bag is for the Marine Corps Crayon, and the Canoe Club crayon and components are in their own bag. I was planning to have them all taped, but I learned hilariously late into assembling the kits that for some reason, tape does not adhere to certain LEDs. Who knew?

If a resistor has come loose in transit the values of the resistor for each crayon are as follows, as well as the LED color:

The Army - Green - 10K Ω
Canoe Club - Yellow - 330 Ω
Puddle Pirates - Orange - 120 Ω
Chair Force - Blue - 0 Ω
Marin Crops - Red - 120 Ω
Star Fleet - White - 0 Ω

If you do not know how to read resistor values here is a handy guide:

![506515 image0](https://github.com/wery67564/Vetcon_Badge_2023/assets/22899183/48ed0444-2a86-4515-85f1-5df64a4c4588)

And yes, those are zero ohm resistors, yes I know, yes yes, please leave me alone. It looks nice.

The LEDs have a positive/negative orientation, the longer leg of the LED is positive, and it will go into the circular pad at the crayon tip, and the negative leg in the square pad. 

The resistor can be soldered to the front or back of the crayon, whichever you prefer, I think the front looks nicer.

The back of the crayon (the side with the crypto gibberish you will never solve) is where the male header goes.
