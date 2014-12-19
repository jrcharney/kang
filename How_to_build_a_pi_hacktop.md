# How to build a hacktop
## Introduction
Before I started using my ODroid as my primary Single-Board Computer (SBC), I used a Rasberry Pi B.  With the introduction of the Rasberry Pi B+, creating a hacktop is so much better.

## What you'll need for this project

* Raspberry Pi B+
* A Raspberry Pi B+ enclosure
* Stick-on heat disappators
* A Motorola Atrix Lapdock (search eBay!) (Don't get the Motorola 100 or 500 Lapdock.  I think the Lapdock for the Motorola Droid Bionic should be OK. The only difference is that the Atirx and Bionic's microUSB and microHDMI ports are on different sides.) Be sure that it comes with the charger.
* 16 GB SD card or larger (8 GB is NOT enough; you can get it cheap at MicroCenter) with a Kang image loaded on it.
* Wifi Dongle (I find Trendnet's N150 to be discreet as well as good enough for any Raspberry Pi or ODroid project.)
* A roll of black industrial Velcro. (About 10 feet. You can find this at your local hardware store. The width should be 1 inch.)
* A pair of fabric shears (used to cut the Velcro)
* 6 to 8 inch USB male (USB male A) to microUSB female cable. We will call this cable "Cable A". (See note below.)
* 10 to 12 inch HDMI male (HDMI type A male) to microHDMI female (HDMI type D female) cable. We will call this cable "Cable B". (See note below.)
* 6 to 8 inch microUSB male to USB male (USB male A) cable.  We will call this cable "Cable C". (See note below.)

The last three items on this list will be hard to find, but it is important that you do not go on to eBay to get them.  With things like ["Rubber Duck"](https://hakshop.myshopify.com/collections/usb-rubber-ducky/products/usb-rubber-ducky-deluxe) devices that could easily be embedded into questionable products, most of them becoming more Chinese in origin, especially for computers, as a security caution, it would be best to stick with a reputable dealer either in the United States or within your own country. (Assuming your country isn't being a jerk about electronic privacy.  A trip to [EFF.org](https://eff.org/) might help.)  I'm trying to think of where is a good spot to get these items.

I prefer wires over adapters as adapters require the need for cutting or breaking something.  If we can avoid that, that would be much better.

I will post links to these items from a site that seems trustworthy enough in the future.

## Instructions
1. Assemble Raspberry Pi by putting the B+ into the B+ enclosure.  Be aware that the B+ enclosure at MicroCenter needs to be put in in a certan direction so that the B+ clips into the enclosure.
2. Stick on the heat disappator.  There should be a larger one that sicks on top of the CPU and a smaller one that sticks on top of the smaller processor.  
3. Add any Pi accessory like a GPIO cable (sold separately) or Camera module (sold separate) or various shields. If you can, then put the top half of the enclosure on. 
4. Place two pieces of industrial velcro on the bottom half of the Pi enclosure.  Do not cover any of the slots or the two mounting holes.  I recommend putting the soft side on the Enclosure and the rough side on the lapdock.  Also, put the rough and soft sides together then use sewing shears to cut a two pieces of slightly smaller than the lenght of the enclosure pieces.  Take the plastic backing off the soft side when sticking onto the enclosure, but not the rough side until we get to the lapdock step.  Industrial velcro is not effective unless the adhesive on the back of the soft and rough sides are stuck on the hard surfaces for more than a few hours.  Choose where to put it wisely!  Alternatively, cutting two long strips of rough side and sticking them at a parallel distance as the softsides on the enclosure might be a good idea, especially if you upgrade to an Odroid or get another Pi. The first piece 2 inches from the hinge of the lapdock and the second piece about 1 1/2 inches above that. (Do that around step 9 later in these instructions.)
5. Plug the WiFi dongle into one of the four USB female slots. The top one in the middle is the best spot.
6. Plug Cable A into a USB female slot.  We recommend the one below where you plugged in the WiFi dongle.
7. Plug Cable B into the HDMI female slot.
8. Plug Cable C into the microUSB female slot.  If you have a Raspberry Pi model B (not B+), this step can be skipped.
9. With the laptop in the closed position, prepare to adhease the Raspberry Pi to the back of the screen.  **DO NOT** place it near the hinge!  Instead put it two inches above the hinge such that the enclosure can't touch hinges and the wires can connect freely.  The second piece should be put about 1 1/2 inches above that piece, parallel to that piece.  It is prefered the rough side is aheased to the back of the monitor rather than the softwide.
10. Open the lapdock, and watch the machine boot up.  If Wifi still doesn't work, you may need to hook up the Pi to a router via Eithernet.  But that is why I recommend that any distro be loaded with Wifi drivers preinstalled.  Kang is such a distro.
