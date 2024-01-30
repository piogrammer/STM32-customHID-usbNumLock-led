![image](https://github.com/piogrammer/STM32-customHID-usbNumLock-led/assets/53431902/5f2e41ee-69a1-479e-b461-abe5c6a3c532)
I was pissed when I bought a new laptop a while back and it didn't have a NumLock indicator light. 
I mean, it's a $6500 laptop, and they couldn't spring for a few cents to include a super useful indicator light? Am I taking crazy pills here?![image](https://github.com/piogrammer/STM32-customHID-usbNumLock-led/assets/53431902/393e6ab9-6225-4451-b785-8645f287786c)

I've seen a bunch of shill videos on Bilibili pretending to be reviews, and they get millions of views, you know, 'cause they're paid promotion by the company. 
If you watch those shill videos, you'll notice that not a single one of them mentions the fact that this laptop doesn't have a NumLock indicator light.
And there's no close-up of that area on the  shopping website（JD.COM） either. 
![image](https://github.com/piogrammer/STM32-customHID-usbNumLock-led/assets/53431902/97453321-eba2-4274-b272-3c6efe806f0e)

So when I got the damn thing in the mail, booted it up, and realized I was fxxked! 
I paid top dollar for a crippled laptop. 
It has a dedicated number pad, but no NumLock indicator light to show you whether the number pad is active. 
Listen, man, I know a lot of people buy gaming laptops just for gaming and don't care about productivity or design stuff, 
but I'm not one of those people.
I often need to do stuff like debug equipment in the field, field coding and testing stuff like that.
Not having a NumLock indicator light seriously hampers my productivity and pisses me off.
So I spent a few hours making my own USB NumLock. It uses an STM32F042F6 microcontroller as the brains,
which is nice because it doesn't need a crystal oscillator. 
The circuit is super simple: just one 1.5k resistor, a few 100nF 0603 capacitors, and a 6206-3v3 voltage regulator. 
The indicator part is made up of four 0603 white LEDs and two 0603 resistors for current limiting, 
with a value of 22 ohms or higher to prevent the LEDs from being too bright and hurting your eyes.
I housed the circuit board in an old, busted 150mbps wireless network card case, and it looks pretty slick.
I've tested it out, and it works like a charm. Thanks to the manufacturer's boneheadedness, 
I had to spend an extra ten bucks to fix their mistake.
If you've also had the misfortune of buying one of these poorly designed laptops, you can make your own USB NumLock too.
![image](https://github.com/piogrammer/STM32-customHID-usbNumLock-led/assets/53431902/e094e779-47ae-4f48-b215-2f80a10326b8)

![image](https://github.com/piogrammer/STM32-customHID-usbNumLock-led/assets/53431902/df91494a-a0d5-4086-8bd9-ab04a280595c)
