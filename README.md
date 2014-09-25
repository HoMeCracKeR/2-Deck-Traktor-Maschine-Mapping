2 Deck Traktor Maschine Mapping
===============================

This is a Traktor mapping for the Native Instruments Maschine. It's for two track decks (A & B) and two effect racks (1 & 2). The main philosophy is simple: As most as possible in direct access.

At first I tried to build a mapping to have everything in control in Traktor with one NI Maschine controller. Also I wanted as much as possible direct on hand. It worked, but just for a very small subset of functionality. To archieve more, I used a lot of modifiers to switch between different modes. And afer a while I find it annoying. I always had to care about the state of the controller. Check the lights to see where I am and which functionality is on which button.

This way I learned that I don't want to modify everything in sequence, one thing after the other. And I don't want to take care about my controller, this way I loose focus on the music.

So I cut down my personal feature list and focus on intuitivity and simplicity. So this is just a two deck control with just two effects. Also I don't like the fact that there are pages for the top two displays (equalizer and fx). It's a compromise and with a second controller (like the X1 or Z1) you eleminate it completely. Oh, and.. there are no cue points currently, because the loop macros work fine for me. But I'm already working on that. See the Ideas section further down.


Here it is.

{<1>}![](/content/images/2014/Sep/Maschine-Traktor-Eq.png)

* In the **group section**, you can control play/pause, monitor out and enable/disable effect 1 and 2 for every deck.
* In the **transport section**, you have control over the loop recorder: Play/Pause, Record, Delete, set loop size and adjust the loop recorder mix amount.
* You have control over the 3-band equaliser and the effect decks in the top two **displays**.
* To adjust the volume of the two decks use the **Volume and Swing** knobs in the **Master section**.
* On the **pads** are loop macros for the both decks. You can set loops and move around with the active loop in the track. There are two loop steps implemented: 1 and 16. Choose for every deck.
* Press Browsing to enter the **Browsing mode**. You can browse the tree and the list by using the **Volume and Swing** knobs in the **Master Section**. To load a track to a deck, press play on the according deck (**group section**, button E or G).
* Press Sampling to enter the **Sampling mode**. It’s activated by default, indicated trough the active led. In this mode quantise and snap is activated by default. Also when you play a track it automatically sync the track to the master clock and set a 4 bar loop.

To make this your own, I strongly recommend to change the parameter names for the effect decks in the Controller Editor.

{<2>}![](/content/images/2014/Sep/Maschine-Traktor-fx.png)

That’s it. I want to keep the mapping as simple and intuitive as possible. If you come up with some interesting mapping solutions, let me know.

Have fun.


**Blog Post**:<br>
http://briefkast.in/traktor-direct-access-two-deck-control-with-loop-macros-and-fx-mapping-for-the-maschine-hardware/

Ideas for the next version:

* Support gratification style effects or something.
* Add Track preparation, maybe seperate in Preparation and Performance mode. This way the cue points become attractive again. Set delete and manage in Preparation mode and just toggeling in Performance mode.
* I want deck D as Remix deck under control.
* I’m looking for a way to copy a track to another deck with all effects and parameters enabled like before.
* I have an idea of a workflow button. For example: In the browser the button loads the currently selected track in Deck A. Next time I press the button the decks are moved: Deck B -> Loop Recorder, Deck A -> Deck B. Then the button enters the browser and I can load a track in Deck A with the button again. Also the track starts to play and set a loop and all controls are set to my defaults (Vol off, etc…). So I can start mixing the next track. Something like this…

