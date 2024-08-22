# The Trinity Keyboard Collection
## Info & Showcase
These are three of my most recent keyboards that I made for some friends and myself. The [Bar](/keyboards/bar) and [Filght](/keyboards/flight) are two ergo-like, ortholinear keyboards, the former with a normal grid ortho layout and the latter with a split-unibody design. The third and final [End45](/keyboards/end45) is a standard stagger 40% keyboard.

The cases of all three keyboards are prototypes. The end-result cases will most likely be made from copper or aluminum. The rotary knob will also be centred between the top and inner-top lip of the case.

The main goal with all three of these was to create low-profile keyboards that would allow the user to type for longer sessions without having to twist their wrists upwards (or to be forced to use a wrist rest), which, for all four of my friends, is the cause of most of the discomfort when typing for prolonged periods of time. Sadly, not one of them was willing to try out an alternative keyboard layout, which was the biggest contributor to comfortable typing for me (I still have nightmares because of QWERTY). The next best thing was to convince them that a minimal distance from key to key was of great value in terms of strain prevention and improved ergonomics (I still feel phantom pain when I think of backspacing on a standard-stagger keyboard all day).

I tried to achieve the low-profile aspect by designing an open-bottom case that requires some electrical/painters tape to protect the PCB from static on your desk or deskmat. This shaves off about 1-5 cm from the keyboard height. Alternatively, the boards are designed to also be usable without a case, in which case (;D) one would have to use one of the spare PCBs as the bottom 'case' part. These can be added with the help of standoffs and the dedicated PCB mounting holes. Note that opting for this with the Flight keyboard might result in a significant height increase, as the MCU is mounted on the bottom of the PCB. The End45 and Bar keyboard also offer the option to mount protective/aesthetic plates over the MCU and along the whole upper body length, if one chooses to use them caseless.

Since these are meant for my friends, I made them based on their wishes: two wanted a standard-stagger 40% (third KB, End45), one wanted a plank-like (second KB, Bar), and the last wanted to see what the hobby and ergo-lifestyle was all about with a unibody-split, column-staggered keyboard (first KB, Flight, I really hope this one progresses to a split+tilt setup ;D). 
All four of my friends are touch-typers (they don't look at their keyboards when typing), all four of them wanted to be able to reach all the necessary keys they use frequently within at most a 1-key distance from home (heavily utilising layers), and all wanted to have a dedicated rotary encoder that they could easily program to their liking (Vial was used for the software of all three keyboards).

The first keyboard, Flight, was inspired by the Corne and is meant as a gateway keyboard into the ergo-boards hobby. Although I myself dove directly into a minimalist split-18-key (Obelisk) and a one-handed 8-key keyboard (ARTSEY), I'd most likely pick a Corne-like keyboard if I were a beginner with little time on my hands for learning new layouts and memorising layers.

The second keyboard, The Bar, was also one of my long-time projects that I postponed multiple times due to fear of working with diodes. Ultimately, after having handwired my first QAZ keyboard (with diodes), I learned everything about how to wire diodes and matrices and got to work. While I am not the biggest fan of plank-like keyboards, I found this one a joy to type on, as does my friend.

The third and last keyboard, End45, was designed to circumvent and improve the things a standard-staggered keyboard fails to do. Firstly, the often unnecessarily gargantuan spacebar, which has been split into two keys to allow for easier layer manipulation. Second, the removal of keys that are infrequent and can be relocated to other layers. And lastly... gaming. While it might seem counter intuitive to not have a dedicated number row when gaming, the two friends who requested this keyboard agreed to try to use their extra mouse buttons (M3, M4, M5 and scroll-wheel) for the necessary numbers that are usually used in FPS games. Suffice to say, they got used to it within a few days and refuse to go back to using the numrow.
### The Bar
![bar keyboard](https://i.imgur.com/GhgdDYq.jpeg)
### The End45
![end45 keyboard](https://i.imgur.com/hH2civK.jpeg)
### Flight
![flight keyboard](https://i.imgur.com/82aj9Le.jpeg)
## JLCPCB
The people at [JLCPCB](https://jlcpcb.com/?from=BWBS) were kind enough to send me these keyboards free of charge to try out their high-end PCBs and 3D printing in exchange for an honest review. For a niche hobby such as this, they offer the most straightforward and hassle-free ordering process, with many options to choose from and try out, all with reasonable shipping fees and many carrier options.

For the bar and flight keyboards, I chose the high-end ENIG finish that has gold around all of the through-holes and pads, making it look quite premium.
For the end45 keyboard I went with the standard, LeadFree HASL version, which is on par with the ENIG one in terms of quality, but has silver-like through-holes and pads instead of gold ones.

As for the cases, I chose the Imagine Black option, which turned out great. I was very pleased and impressed with how level the parts were, as other prints from different 3D printing service providers were very weak and bent, despite the same settings: 100% fill, SLA(Resin). Shortly after uploading the files, I was notified that there might still be some potential bending but none of the dozen or so cases had any. The tolerances for this SLA+Material combo were also perfect, which makes it very reliable to work with and prototype. To test the limits of said tolerances, I also made a few small prototype rotary knobs that came out great and fit perfectly as well.
There were only two mild imperfections with the 3D-printed end45 case, and all of them were on the surface (see top-left of end45 case). Furthermore, there were quite a few smudges of something oily on all of the cases, presumably from the sanding process (see keyboard case pictures), but this was easily fixed and cleaned with isopropyl alcohol.

Regardless of their contribution to this specific project, if you plan on making your own keyboards I would highly recommend [JLCPCB](https://jlcpcb.com/?from=BWBS). I have used their services for over two years and have been very satisfied with the speed of production and the general quality of their products. Furthermore, their customer support is very quick to respond and always kind and helpful.
#### PCB Order Process
These are the options of note that I used when ordering my PCBs for the [Filght](/keyboards/flight) and [Bar](/keyboards/bar) PCBs. Everything else was default:

| Specifictation | Chosen Option |
| -------------- | ------------- |
| PCB Thickness  | 1.6           |
| PCB Color      | Black         |
| Surface Finish | ENIG          |
| Mark on PCB    | Remove Mark   |

And these for the [End45](/keyboards/end45) keyboard. Again, everything else was default:

| Specifictation | Chosen Option |
| -------------- | ------------- |
| PCB Thickness  | 1.6           |
| PCB Color      | Black         |
| Surface Finish | LeadFree HASL |
| Mark on PCB    | Remove Mark   |
#### Case Order Process
For the case and rotary knob prototypes:

| Specification  | Chosen Option   |
| -------------- | --------------- |
| 3D Technology  | SLA(Resin)      |
| Material       | Imagine Black   |
| Surface Finish | Yes             |
| Sanding        | General Sanding |
