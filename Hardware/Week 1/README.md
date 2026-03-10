## Fading LEDs

For week one of Resolution Hardware, I made a circuit which turns on a few LEDs, each with a small delay. This sounds easy, but as a total novice to hardware it took some time to get right.

First, I needed to figure out why my second led only burned if I put it in a series circuit. Apparently, this was due to the minimum voltage and the capacitor blocked this. I also learned about time constants, and what a resistor and capacitor even do. It was really cool and I liked that the tutorial only explained the basics, and that you needed to do your own research to make your own final project.

Here is the demo: https://is.gd/UC9o0z

### How it works
First, we have a power source, which is routed to five LEDs in parallel. Each of them has its own capacitor and resistor. Each one has a different value. This creates a 'fading' effect.

https://github.com/user-attachments/assets/d3d1ed24-11d6-4dfc-91a0-f55e3def1991

