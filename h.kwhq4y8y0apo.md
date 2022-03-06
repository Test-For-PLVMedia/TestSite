BOAC (Baby of all Cases)
========================

BOAC, the MOAC’s little brother, powers streams that don’t need (or can’t have) the full MOAC. It lacks a replay machine, a hub, an external switcher (though you could theoretically use it), and some of the niceties of the MOAC. It is, however, still a powerful machine, and you can easily produce a great stream with it nonetheless.

Setting up During a Stream
--------------------------

\[TODO: Pictures\]

1.  Take off the front and back panels.
2.  Find the power plug for Wirecast (already connected in the case), and plug it in. It should be labeled TO WIRECAST on the plug.
3.  Plug in wirecast monitor and peripherals (mouse, keyboard). Don’t forget monitor power.
4.  Plug in the barrel plug (power) for the switcher. It should be hanging just below its port, we unplug it so it doesn’t get crushed when we close the case.
5.  Find the UPS power plug in the back, and plug it into a surge strip. It should be labeled TO WALL on the plug.
6.  On the UPS (front side, bottom), open up the little clear plastic cover and press the power button. This turns BOAC on.
7.  If it doesn’t start up with the UPS, turn Wirecast on (open up the front panel, flip the black switch).
8.  Plug wall ethernet into the WAN1 port on the network switch.
9.  Plug in ethernet for Wirecast, Switcher, and the Laptop.

1.  The cables for this should already be connected to the network switch. Simply find the loose ethernet ends and plug them into wirecast/switcher.

10.  Connect the PROG SDI BNC port on the switcher (right side) to the Wirecast input BNC port (wirecast only has one BNC port, it’s that one).
11.  Plug cameras into Switcher (left side, read labels).
12.  Reference [Wirecast operating](h.k6vpdgk5q6kp#gfxwirecast) for Wirecast software setup.
13.  Operate Switcher on laptop \[TODO: Link to section\]

### Tearing Down

Tearing down is effectively the same as setting up but in reverse, but please keep in mind that:

1.  You must unplug the power for:

1.  Switcher
2.  Wirecast (after shutting down properly from software or front panel)

2.  You must disconnect the program SDI going between Switcher and Wirecast
3.  You must disconnect ethernet for Wirecast

We do this so that the back case does not crush these connections when we close it.

General Layout and Case Setup
-----------------------------

![](images/image26.png)![](images/image62.png)

![](images/image81.png)

Above you can see the internal connection layout of the BOAC. See [Connections](h.kwhq4y8y0apo#connections) for more information on what you need to connect.

Connections
-----------

To get the BOAC up and running, you will need to connect:

*   Network (detailed above in [Setting up During a Stream](h.kwhq4y8y0apo#setting-up-during-a-stream))
*   Cameras to Switcher
*   Power to Wirecast (we unplug this because it doesn’t fit in the case).
*   Switcher PROG OUT to Hyperdeck (this is the light blue cable coming from the top)
*   Switcher PROG OUT to Wirecast SDI In

Switcher - ATEM TV Studio
-------------------------

Everything is effectively the same as the [MOAC](h.saa8t5379qfj#switcher-atem-tv-studio-pro-4k), just instead of using the physical switcher control surface you use the virtual one on the laptop.

* * *