# The Fin
## v1.03

![Red in Hand](/Images/redInHand.jpg)

### PRINT AT YOUR OWN RISK. AS OF V1.03 THIS BLASTER IS FUNCTIONAL BUT VERY FINICKY AND HARD TO BUILD. YOU HAVE BEEN WARNED

### Intro
The Fin is a straight Talon mag fed pump action springer in a small compact frame. Coming in at around 15in (390mm) long! The blaster packs an Espyr spring volume with a side mounted mag to help keep the blaster compact (this is also how I came up with the name for it). Two threaded rods make up the trigger mechanism and the reload action. The rods are hidden behind the center shroud for aesthetics. The blaster utilizes a turn-around much like the Lynx or SLAB to transfer backward airflow into dart throwing power. Picatinny rails or just some iron sights are planned, I just wanted to get one printed to work out any bugs before more design work.

### The Fin: A Reflection
This project was an amazing learning experience for me. It was one of the first “large” scale design-to-fabrication projects of mine that actually ended in a functional thing in the end. That being said, the blaster is not without its issues…

##### The Bad:
This blaster has some fundamental design flaws. The air seal is not great, the trigger is not reliable, the reload mechanism is fragile at best, the threaded rods are hard to install/tweak, and the blaster assembly process is nightmarish. 

The biggest of the problems is definitely the trigger mechanism. Of the 4 blasters I built on the v1.03 design only half of them had a working trigger. The pressure on the catch from the spring force was enough to prevent the rudimentary two ramp trigger system from working at all. The catch would get to a point that the trigger wouldn’t apply enough force to move it resulting in a stuck catch and a non-functional trigger. My hypothesis as to why this happens stems from print tolerances. If the space between the plunger cup and catch cylinder is too big then the spring creates a rotational force that pinches the catch at the top and bottom of the bracket. So instead of the catch dispersing force across a large area on the cup it is focused to one point on both the cup and cylinder preventing downward movement. Brief scribble below shows this:

![plungerCatchIssueHypothesis](/Images/plungerCatchIssueHypothesis.jpg)

I believe the fix for this is to design a new trigger mechanism. I have some ideas to do this but still need to design them. The challenge is fitting the design into the rather limited space given by the design.

The air seal and reload mechanism go hand in hand so fixing one might help the other. During our “Beta Test War” one of the two working blasters stripped the pusher off from the threaded rod in a rather intense reload. Currently the threaded rod is just screwed into the plastic of the pusher bracket so if enough force is applied then the rod can strip out of the hole rather easily. The easiest solution is to add a captive nut to the pusher bracket to alleviate some threads on plastic failure but this would increase the profile of the reload bracket and possibly hit the user in the hand during reloads. Another solution might be to move the location of the threaded rod or eliminate it altogether.

The air seal issue is a partial oversight on my part. The magwell and magwell top have two halves of the barrel seal designed into them. This creates a gap that the air can escape from when the blaster is fired. Putting the entire arc into one of the pieces might fix this issue.

The threaded rods were an interesting concept to utilise but in practice caused significant issues especially during assembly. Having them thread into both sides of the reload and trigger mechanism meant that the tweaking their placement involved disassembly of the blaster. They offer a clean way of transferring force from one side of the blaster to the other but I feel that in possible revisions or future projects I will just use aluminium bars instead.

The biggest elephant in the room is the assembly… it is not anywhere close to user friendly! This is definitely an “implementation of design” problem. After assembling this blaster about a dozen times I was able to get it down to about an hour to get everything together and functional. It is not intuitive or user friendly in any way. I definitely learned quite a lot here haha.

##### Some “Key Takeaways”:
- Decrease the amount and variety of screws. The blaster utilises 11 different kinds and sizes of screws. Some of the screw holes could be redesigned to use a different screw size easily. I estimate that I could cut the variety of screws in half just with some slight model tweaks.
- Use different screws. I am impartial to M3 hardware but the button head screws I am using here are fragile and easy to strip. Socket head are definitely the way to go.
- Don’t do “screw into plastic” everywhere. Utilise captive nuts as much as you can. It is very easy to over tighten and strip out 3d printed plastic.
- Clearance Clarence… this is one of my first big, multi-part 3d printed projects and the tolerances stacked HARD at times.
- Off the side mags are interesting and cool visually but in practice get in the way. Especially if they are close to the body like on The Fin.

##### What's to come:
At the current moment I don’t know if I want to continue working on this blaster or take what I have learned and move on. Figuring out the trigger and air seal might be all this blaster needs to be classified as “Done” but at the same time I am rather burnt out on it. In the end it was a great experience and I enjoyed it quite a lot! This is not my last blaster by any means, I will continue to develop and release designs that I think are cool.

Here is a list of things that need to be fixed or additions to the platform that I think would be good/helpful/interesting.

- Fix the air seal
- Fix the trigger mechanism
- Add sights or picatinny rail mount
- Add options for different front grips. (Picatinny rail, built in foregrip, etc)
- Add stock
- Add a return spring?

# The Design

![Group of built blasters 1](/Images/groupSideView2.jpg)
![Group of built blasters 2](/Images/groupSideView1.jpg)
![Group of built blasters 3](/Images/groupTopView.jpg)

![Blue Blaster](/Images/blueWithMag.jpg) ![Orange Blaster](/Images/orangeWithMag.jpg) ![Red Blaster](/Images/redWithMag.jpg) ![White Blaster](/Images/whiteWithMag.jpg)

Here is a imgur link to some renders of the blaster: [OLD](https://imgur.com/a/9urtGti)

# Changelog
<details>
<summary>Changes</summary>

- 12-29-2022: A Reflection...
  1. Added Images, a reflection, whats to come

- 12-21-2022: Additional Changes After Second Build (v1.03)
  1. Updated Parts
     - **Magwell Top**
       - Updated dart guide so the *Pusher* O-ring does not rub against it
     - **Magwell**
       - Updated dart guide so the *Pusher* O-ring does not rub against it
     - **Trigger Catch**
       - Add clearance between *Trigger Catch* and *Front Spacer* (missed in previous release, changes were present in step file though)

- 12-20-2022: Updates After Second Build (v1.02)
  1. Updated Parts 
     - **Grip Core**
       - Implement new trigger spring design
     - **Grip Core Plate**
       -  Implement new trigger spring design
     - **Pusher**
       - New keyway design
     - **Turn Around**
       - Update slot for new keyway design on *Pusher*
     - **Turn Around Spacer**
       - Update slot for new keyway design on *Pusher*
       - Update clearance for *Pump Grip*
     - **Magwell**
       - Update slot for new keyway design on *Pusher*
     - **Magwell Top**
       - Update slot for new keyway design on *Pusher*
     - **Center Block**
       - Update clearance for *Pump Grip*
     - **Pump Grip Core**
       - Add cutaway to give access to screws attaching *Reload Block* to *Plunger Catch Cylinder* (Makes assembly easier)
     - **Reload Block**
       - Add clearance between *Reload Block* and *Front Spacer*
     - **Front Spacer**
       - Add clearance between *Front Spacer*, *Reload Block*, and *Plunger Cylinder Catch*
  2. New Parts
     - **Plunger Catch - Medium**
       - Keyway in the *Plunger Catch* cut in half
       - Use if your tigger is too hard to pull because of the compressed spring force on the *Plunger Catch*

- 12-15-2022: Huge Design and Clearance update.
  1. Updated Parts (v1.01)
     - **Center Block**
       - Formerly *Plunger Lock Block*
       - Updated screw holes, support bar, and barrel clearance
       - Added chamfer for easy plunger tube insertion
       - Added clearance for Pump Grip
     - **Front Spacer**
       - Updated support bar and barrel clearance
       - Updated clearance for trigger catch
     - **Fronter Spacer**
       - Updated support bar and barrel clearance
     - **Grip Core**
       - Decreased internal support structure to save plastic
       - Updated screw hole clearance
     - **Grip Core Plate**
       - Added clearance between Grip Core and Grip Core Plate
       - Added support structure to keep trigger way square
       - Updated screw hole clearance
     - **Grip Left**
       - Updated screw hole clearance
       - Updated Google Drive file link
     - **Grip Right**
       - Updated screw hole clearance
       - Updated Google Drive file link
     - **Mag Release**
       - Added clearance between Mag Release, Magwell, and Magazine
       - Updated screw hole clearance
     - **Magwell**
       - Added clearance for Magazine
       - Adjusted Trigger Bracket clearance
       - Updated screw hole clearance
     - **Magwell Top**
       - Added features to make part easier to print
       - Removed part of bracket that interfered with Turn Around
       - Updated screw support structure between Magwell Top and Turn Around
       - Updated clearance for Magazine lips
       - Updated clearance for screw holes and Pusher
     - **Nose**
       - Updated support bar and barrel clearance
     - **Plunger Catch**
       - Formerly *Plunger Catch Release*
       - Redesigned for new square Plunger Shaft
     - **Plunger Catch Cylinder**
       - Formerly *Plunger Cap Cylinder*
       - Added clearance for new Plunger Shaft
       - Updated screw hole clearance
     - **Pump Grip**
       - Removed some structure to make clearance for screw heads off of the Center Block
       - Updated screw holes and support bar clearance
       - Updated Google Drive file link
     - **Pump Grip Core**
       - Removed some extra structure to save plastic
       - Updated screw holes and support bar clearance
     - **Pusher**
       - Added clearance between Pusher, Magwell, and Magwell Top
       - Updated screw hole clearance
     - **Ram Bracket**
       - Moved screw head cut-out to accommodate new screw support structure on the Magwell Top and Turn Around
       - Updated screw hole clearance
     - **Reload Block**
       - Formerly *Plunger Cap Block*
       - Added clearance for Pump Grip and Spacers
       - Updated screw hole clearance
     - **Short Plunger Cup**
       - Modified part to accommodate new square Plunger Shaft
       - Added internal structure to support new square Plunger Shaft
       - Updated screw hole clearance
     - **Trigger Catch**
       - Updated threaded rod hole size
       - Modified ramp to accommodate new Plunger Catch
     - **Turn Around**
       - Removed O-Rings from plunger tube and barrel well
       - Updated screw support structure between Magwell Top and Turn Around
       - Adjusted Trigger Bracket and Pusher clearance
       - Updated screw holes, support bar, threaded rod, and barrel clearance
     - **Turn Around Spacer**
       - Updated support bar, threaded rod, and barrel clearance
       - Adjusted Pusher clearance
  2. New Parts
     - **Plunger Cap**
       - Removed shaft from Short Plunger
       - Added structure to attach Plunger Shaft
       - Changed 3 1/2 inch machine screw to 2 inch, Still #10-32
       - Adjusted O-ring clearance
     - **Plunger Shaft**
       - New square shaft and key
  3. Removed Parts
     - **Short Plunger**
       - Split into Plunger Cap and Plunger Shaft
       - Old design did not withstand the forces of a compressed K25 spring

- 12-05-2022: Added drill stencil STL files for support bars

- 12-04-2022: Initial Release  (v1.00)
</details>

<!-- BOM -->

<!-- Assembly Video -->

<!-- Q&A -->
