---
title: "Very Cool Latch D"
github: "https://github.com/Gabinan890/Latch-D-with-BJT"
description: "A simple Lacth D very cool and absolutely useless built with some BJT transistor :),\na Latch D it a single memory cell of 1 bit  in particular the lacth D is the most simple element of memorization."
created_at: "2026-10-25"
total_time: "5h"
---

# October 26, 2026: I've built the essential piece of my project

It's not my first time trying BJT transistor but I've always used transistor from the series S90 now I'm trying the model BC547, I've built first a logic gates NOR whit 2 transistor it was simple just connect the two collector, provide the power to one of the collector node, connect all the emitter to gnd, and most important use the correct resistor (thanks to my bench power supply I've saved many component from burning cause I've used the wrong resistor), one of the problem when I've switched from the S90 series to the BC547 transistor was the pinout it's very important al the time study the pinout for save your time and your component, however a NOR gates it's a binary operator wich mean that read two input and provide a single output from the truth table of the NOR gate we can see that only if both input are 0 it provide 1, so using two NOR gates I've built a Latch SR that is one of the simplest asynchronous circuit that memorize an information of one bit, well for building this Latch SR I've followed the instruction of my school telecomunication manual that explain circuit like the Lacht SR and other types of Lacth and Flip-Flop using logic gates so I've just studied all the concept and replaced the logic gates with my BC547 transistors, for creating a Lacht SR you need just of two NOR gates that we call NOR1 and NOR2 each of them with two input A and B, I've just connected the input B of NOR1 to the input of NOR2 and the input A of NOR2 to the output of NOR1 so now I've got my Lacht SR the input A of NOR1 it's called S (that mean set) and input B of NOR2 it's called R (for reset) and the two output are called Q and NOT(Q), in my circuit the led below is the output NOT(Q) and the led above is the output Q.

![](https://fabricate.hackclub-assets.com/ef23ec6a327622bff84ff7b603b611f849df813b065310574b414b0ef2a9844a/video-mp4/WhatsApp%20Video%202026-10-26%20at%2019.20.43.mp4)
![](https://fabricate.hackclub-assets.com/885d67de05132beaf117c5f0a053eccf5d9aaf4aa5f69b99e6fa1fb77c1d78e4/image-jpeg/WhatsApp%20Image%202026-10-26%20at%2019.52.31.jpeg)

**Total time spent: 2h**

# October 27, 2026: I've studied the next steps for my project

Well... Today at school in informatics class and the lesson about cout and cin on C++ was so boring so I've picked my pen and my notebook and I've drew some schematics and I've planned how to build a Latch SR with enable and a Latch D(My goal :D), so using my telecomunication school manual as a reference I've studied a Latch SR with enable that's basically a Latch SR but using two AND gates select if read or not the S and R input using a third input E (for enable), then the Latch D that's a Latch SR with enable but connect the S input to the R input with a NOT gate merging the two input in just one input called D (for data) it's very important because in this way S and R cannot have the same value at the same time. All this studying was good but I've wanted to try a thing at school cause I was just planning the circuits to build them at home I've wanted to use the BC557 transistor that are PNP transistor (BC547 was NPN) well in RTL logic it's very unusual using PNP transistor but i was thinking that maybe it can work so I've used two BC557 for build a single AND gate then the second for build the Latch SR with enable but when at home I've build the circuit I've realised why in RTL logic PNP transistor are not much used, I've built an AND gate with two BC557 it worked but PNP transistor are not much stable and I was on a breadboard so when I've clicked one of the button the output was not a perfect 0 cause the led turn on even if the light was very low but in the truth table of an AND gate we can see that an AND gate must return 0 if one of the input is 0, so I've not done much but I've learned how to use PNP transistor and also it's always good test new things but I think that after today I will stay with NPN transistor that are more stable for my experiment. :)

![](https://fabricate.hackclub-assets.com/ed229f333a26cbe930db8f260f69668527e98a1a6b5403ab7efa7ae2fb88260b/image-jpeg/WhatsApp%20Image%202026-10-27%20at%2014.18.57.jpeg)
![](https://fabricate.hackclub-assets.com/080c03da90ee5d7844fffa59d72c5872f306094666dd317687de92949d3cc52d/image-jpeg/WhatsApp%20Image%202026-10-27%20at%2014.18.56.jpeg)
![](https://fabricate.hackclub-assets.com/d53f3534b1d7eb55db4f3119dd25a199e6441c4b92d9d31aab07a49314e242c6/video-mp4/WhatsApp%20Video%202026-10-27%20at%2015.14.58.mp4)

**Total time spent: 3h**
