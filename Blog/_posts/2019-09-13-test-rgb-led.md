---
title: "Is This RGB LED Common Anode Or Common Cathode?"
tags:
  - "electronics basics"
---
Say you have a multi-color LED laying in your components bin and you don't remember whether you bought a common cathode or common anode! How to you find out? It's fast and simple with the continuity / diode test on your multimeter!

LEDs are diodes and only allow current to flow in one direction (RGB LEDs are of course no different). If you were unaware, to test the polarity of a regular LED, you can use the continuity test mode on your multimeter. Put the black/common multimeter test probe on one lead of the LED and the red probe on the other. If the LED dimly lights up, you know the lead being touched by the black test probe is the cathode. If it doesn't illuminate, turn the LED around and it should light up with the test leads on the other LED leads. (Check out more pictures at the end of the post.)

{% include image_caption.html url="/assets/images/test_rgb_led/White.jpg" caption="With the black probe on the short lead, the LED lights up" width="100%" %}

Testing a RGB LED is very much the same, but you test continuity between the common lead and one of the 3 other leads. If you don't know which is the common, it should be the longest lead. If that doesn't help you, there should be a flat side or notch on one side of the LED. The common should be the second lead from that side. With the black probe on common, touch the red test probe to one of the other pins. If the LED lights up, you know that the common lead is the cathode. If it doesn't, try the red test probe on the common LED lead and the black probe on any of the other leads. Illumination with red on common means common anode. You can also test which lead is what color this way since the continuity test between common and one lead will light up one color.

{% include image_caption.html url="/assets/images/test_rgb_led/Blue.jpg" caption="With the black probe on the common and the red probe on another lead, the LED lights up. That means this one is common cathode. And as you can see, that lead is for blue" width="100%" %}

I wrote this short blog post because I didn't see this useful tip with a quick google search of "how to determine if a RGB LED is common anode or common cathode" and thought maybe someone might find their way to this dark corner of the internet and this might help them. Below are some more pictures to help illustrate this tip.

{% include image_caption.html url="/assets/images/test_rgb_led/LED_Backwards.jpg" caption="With the probes on opposite leads, the LED doesn't light up" width="100%" %}
{% include image_caption.html url="/assets/images/test_rgb_led/LED_Labeled.jpg" caption="The longer lead on a LED is the anode. The lead by the flat side is the cathode" width="50%" %}
{% include image_caption.html url="/assets/images/test_rgb_led/RGB_Labeled.jpg" caption="Note the flat side and the long common lead" width="50%" %}
{% include image_caption.html url="/assets/images/test_rgb_led/RGB_Backwards.jpg" caption="With the red probe on the common, the RGB LED doesn't light up because it is common cathode" width="100%" %}
{% include image_caption.html url="/assets/images/test_rgb_led/Red.jpg" caption="The first lead is for red" width="100%" %}
{% include image_caption.html url="/assets/images/test_rgb_led/Green.jpg" caption="The third lead is for green" width="100%" %}

(This post has been migrated from my old blog)
