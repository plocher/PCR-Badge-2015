### The best laid plans ...   sigh.

We ran into two problems with this project - one easy to fix and
the other, well, not so much...


1. The grab bag batch of Red LEDs (1 pound for a dollar or some
such bargain...) was too good to be true - 20% of the LEDs turned
out to be defective - including all three I used on the initial
bring-up board.  If nothing else, it was an interesting debugging
experience and a lesson in the true cost of being cheap :-)


2. Once I got the blinking LEDs sorted out, everything else tested
out OK - except for the IR sensor.  More debugging, trace following,
scope probes - all showed that "it should be working" - except it
didn't.  Until the AHA! moment when I realized that, no matter how
many times I tried to analogRead(D7), it wouldn't work (Doh!).  This
one is all my fault - I was revising a schematic late at night,
just before the fab deadline, trying to squeeze out just one more
IO pin to do something interesting, while at the same time cleaning
up the board layout.  Obviously by moving some connections from
here to there - after all, they are just labels on the CAD screen...  
This could be "fixed" by cutting traces and running jumper
wires, which, while it would certainly make the project more
realistic, wouldn't make any friends at the convention.  I decided
to drop the feature and pull the unused parts out of the kit bags.  Sigh.


We distributed 20 kits at the show - enough for us to almost recoup
our BOM costs - and had two people spend their afternoon assembling
their kits - one of whom had never soldered before!
(his badge worked the first time, too!)


Success!



