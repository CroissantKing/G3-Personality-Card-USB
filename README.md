# G3-Personality-Card-USB

Later revisions of the Personality card that comes with every Beige G3 have footprints for a single/dual USB 1.1 socket and supporting circuitry, similar to that found on early USB PCI cards. There are three types of Personality card - the Whisper, the Wings, and the Bordeaux; all three potentially have the footprint.

Prototype machines have been seen with this USB socket, but no production machines ever had it installed. We don't know if it was at one point planned for the beige to have built-in USB, or if the footprint was meant solely for developement.

I have a soft spot for the Beige G3 and was thrilled to find it has this 'secret', hidden feature and given nobody else has tried to get it working I jumped in. I initially soldered in a CMD 0670 chip taken from a donor PCI card, and, with the help of other forum members at 68kmla, I worked out the values of the capacitors and resistors that are required to get the USB circuitry working. Other key components included a 5V oscillator, a polyfuse and of course the USB port itself.

So far, testing has shown the USB portion of the Personality card to be fully functional and reliable under Mac OS 9.2.2 and Mac OS X 10.2.8. The USB portion of the card is seen as a PCI card in slot 'PERCH' and therefore relies on the same drivers (and has the same limitations) as a traditional USB OCHI PCI card would.

Peter Baran
24/5/2023
