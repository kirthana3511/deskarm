# Desk Arm Build Journal  
Design Phase Edition

Total Hours: 57.5

---

## June 1

Alright. Pulled up to June with one mission. Build a robotic arm that slaps—something desk-friendly but not weak. Started by writing down all the vibes I wanted this thing to have. Clean motion, no jittery nonsense, decent load handling, and easy modular upgrades. Got inspired by a random Reddit post that showed a 4DOF arm and said screw it, let's go for 6.

Binged YouTube till my eyes hurt. Sketchy CAD models, 3D printed arms, some sketchy spaghetti wiring—plenty of ideas. But I wanted mine cleaner, more compact, and built like a tiny tank.

**Hours Spent**: 3.5

---

## June 2

Got obsessed with joints today. Spent hours just thinking about how each joint would rotate, how much range is too much, how I’d actually assemble this without needing a literal factory setup. Built a rough hinge design in Fusion 360. Spoiler: it was trash. But it helped me figure out what not to do.

Tried using some parametric constraints but didn’t understand half the terms. Had to backtrack and rewatch CAD basics tutorials. Built a prototype base joint that looks... fine. Kind of.

**Hours Spent**: 4

![image](https://github.com/user-attachments/assets/c06c35bc-acca-4b25-95fd-63a75ca09c80)


---

## June 3

Focused only on degrees of freedom and what each axis should realistically cover. Not gonna lie, 6DOF sounds cool but it’s a whole headache. Thought about going 5DOF for a second but nah. Went deep into inverse kinematics rabbit holes and came out mildly traumatized.

Also tried roughing out the arm length ratios. Made a few paper mockups to check reach. Found the golden middle between “cool to look at” and “won’t knock over my coffee.”

**Hours Spent**: 5

![image](https://github.com/user-attachments/assets/a18f1d0c-456b-476b-aeac-52fa145b9339)



---

## June 4

Fusion 360 was open the whole day. Decided to fully model Joint 1 to 3. Took forever to get one link fully constrained without Fusion yelling at me. Finally got a clean revolute joint setup that moved like butter. Added some visual textures just for vibe. 

Also made a fake payload block to simulate weights. Planning to use it later for balance and center of mass calc. Might even animate it just for clout.

**Hours Spent**: 6

<img width="372" alt="image" src="https://github.com/user-attachments/assets/388d295a-ada2-45ce-8cbe-6e28ef5920eb" />


---

## June 5

Started mapping out the electronics zone. Even though I’m not buying stuff yet, I wanted to block out where the microcontrollers and drivers would mount. Created a dummy PCB block with dimensions of the Feather M4. Mock-mounted it on the base. Looked clean. Left enough spacing for cables too.

Tried sketching the wiring path in 3D space using construction geometry. It’s looking futuristic now. Might throw in a hidden compartment for the power stuff.

**Hours Spent**: 5.5

<img width="197" alt="image" src="https://github.com/user-attachments/assets/21380388-6928-4066-9931-57a9dda4ce94" />



---

## June 6

Took a detour today and mocked up a gripper. Still not sure what I’ll actually use to grip stuff, but made a two-finger claw design with a servo slot. Super basic. Might need worm gear or rubber padding, but that’s future me’s problem.

Watched 2 hours of industrial arm gripper demos. Got hyped. Tried copying one with 3 joints and instantly regretted it. Dialed it back to something printable.

**Hours Spent**: 4.5

![image](https://github.com/user-attachments/assets/a9d968e7-87a9-4501-b70a-f2fa2e19ad1a)


---

## June 7

Back to base design. It hit me that this thing’s gonna need to absorb a lot of stress, so I reworked the bottom plate to be chunkier. Designed bolt holes, made countersunk slots, and tested MDF thickness options.

Also mocked up an enclosure for the control unit. Honestly might 3D print that one just so I can slap a logo on it. Desk Arm deserves a brand moment.

**Hours Spent**: 4

![image](https://github.com/user-attachments/assets/7822d40f-0dfe-4906-b1d6-0b8cd85a3b7a)


---

## June 8

Started compiling all the components I think I’ll need. Motors, drivers, PCBs, cables, fasteners, bearings, antennas—all that. Didn’t buy anything yet, but made a BOM sheet and cross-checked prices across Indian and international sites. Budget’s already looking wild but still in range.

Also color-coded my CAD components based on what’s 3D printed, laser cut, or bought. Super satisfying.

**Hours Spent**: 5

<img width="454" alt="image" src="https://github.com/user-attachments/assets/f11da48e-2923-4148-9080-50ec8335ecbb" />


---

## June 9

Mock-assembled the entire lower half of the arm virtually. Screwed up tolerances twice and had to re-constrain half the model. But the vibe is real now. It rotates, bends, and it’s actually starting to look like a robot.

Added motion limits to joints so I don’t get unrealistic flexes. Thinking of simulating full movement sequences soon.

**Hours Spent**: 6

![image](https://github.com/user-attachments/assets/9566b0d1-dc71-4823-95c1-20fd7dfc7978)


---

## June 10

Final review of the design phase. Went over all constraints, rechecked joint clearances, planned out the wiring tunnels inside the links, and sketched final cross-sections for 3D printing. Made notes for all STL exports. Labeled everything.

Desk Arm’s design is basically locked in now. Ready to hit that order button soon and bring this thing into the physical world.

**Hours Spent**: 5.5



---

