# FLEXPOD
#### TPU X ALU Wire Tripod
>By Aaron Zhan

Hello there! Thanks for stopping by!
## Introduction
I am a maker, 3D printer, inventor, and creative film-maker! 
(Though you can say those are a bit of a stretch, as I am learning new things almost every day). 
I tend to film Youtube videos with my phone, 
but I have always struggled to have a good yet simple camera/tripod setup. Mounting 
a camera is a struggle for anyone trying to take photos or videos (newbies and pros alike).
The main problem with tripods are that they aren't _flexible_ as int he sense that you can only use them in flat surfaces
and it is quite a hassle to adjust and set up (turning knobs, etc)
Luckily, the Gorilla Pod was invented. The Gorilla Pod (and other designs) feature 3 or more flexible
legs that can flex and adapt to the surface/object the tripod is to be mounted onto.
They are great products, and they are quite a hit!
However, if you are a fellew 3D printer, you would instantly have the instrusive thought of: "Can I 3D print that?"

Well, I tried that. And it went South. Some issues experienced with the Official Gorrila Pod was expereinced: 
the friction between the articulated links would gradually wear down. This would happen even whith the TPU bands around the links.
Well, there are variants of the gorilla pod where the legs are made out of 3 pieces of continuous metal that is flexible yet rigid
This design seldom loses its strength and thius its effectiveness. 
And with some inspiration from Reddit, I decided to make the tripod.
## Design Inspiration
So I had found a 3D printed Gorilla Pod design from My Mini Factory. It was honestly quite a clever design, taking great inspiration from the Original Gorilla Pid. It uses 3D printed segments in hard plastic (PLA, PETG, or ABS) and used some TPU connection parts (as "rubber bands" to connect and clamp down on the ball joints).
Again, worked _decently_, but after some extended use, the friction between the joints would wear down.
Luckily, I saw a reddit post: https://www.reddit.com/r/BambuLab/comments/1m8kska/aluminum_wire_in_tpu_is_my_new_favourite_thing_to/
and that gave me a lot of inspiration. I immediately saw some great insight in their design, and I thought I could make something amazing (even better) out of it. The designs mentioned in the Reddit post included many different uses, but being a content creator, I got excited at the sight of a tripod.
The Reddit user mentioned that 5mm craft wire was quite strong and flexible, so that's what I decided to go with. The Reddit user
also mentioned that stacking thin rectangular craft wires didn't cut it - it was too flimsy. This was perfect insight for me, since I didn't have to 
experiment with the different types of wire. The Reddit User's design uses a TPU print and embedding the wire into the TPU print. This is a clever 
way to accomplish the task, but it poses some problems that I identified: 1) The Aluminum Wire is not always straight and tidy, so embedding in the print may be
hard to accomplish and 2) If you want to remove the aluminum wire or swap it out for some reason, you'll have to destroy the TPU print. Embedding in the middle of the print job
is quite a hassle - bad for automation and user experience.
<img width="1000" height="500" alt="Screenshot 2025-11-09 at 11 44 03 AM" src="https://github.com/user-attachments/assets/76faf82e-8b94-40f4-b4e7-42b0134304b7" />
> The slits and 5mm hole enable a smooth experience when inserting and flexing the Aluminum Wire

## Design Innovation
And that's how my design was inspired and improved upon. FlexPod features easy-to-use TPU legs where you simply slide in the Aluminum Craft Wire (5mm, and generous tolerances were added!). This removes the hassle of pausing a print, making the process a whole lot easier! In addition, the leg takes advantage of the Pythagorean Theorem to be oriented on the build plate - you can get a 300mm long TPU leg out of a 220x200mm build plate! Some future plans include making an even longer TPU sleeve - possible oriented in a spiral - for those that need extra long tripod legs. The TPU 3D printed sleeves feature a repeating "slit" pattern, which alleviates stress and enables the TPU to be more flexible (and comply with the bending Aluminum Wire). These slits also reduce friction, enhancing the assembly process. For mounting, I included a simple m5 screw that is secured from the underside of the tripod. I know that people may have different variations of screws available, so the .f3d and .step files are included! m3 screws are used to mount the legs onto the base. The simplicity of the design is good to note! As for the model, I created a phone clamp that was remixed from a popular (and in my opinion, the best) phone clamp: https://www.printables.com/model/25969-tripod-mobile-phone-clamp-v2
<img width="557" height="596" alt="Screenshot 2025-11-08 at 9 48 06 AM" src="https://github.com/user-attachments/assets/77e6dc70-84ae-44d2-9335-98e8fcc18b68" />
> TinkerCAD is (sometimes) better than Fusion at _simple_ tasks!

###### lol a remix of a remix
So I simply took the base of that model, and combined it with the "base" of my Tripod in TinkerCAD (TinkerCAD is better at doing simple operations on STLs - you can do this in Slicer software as well).

## Materials Needed
I know there is a BOM, but this is probably more helpful
- Aluminum Wire
- m5 nuts and screws
- m3 nuts and screws
- TPU & PLA (or other rigid filament) for 3D printing

## Assembly and Manufacturing
FlexPod only has 5-7 printed parts in total (depending on how complicated the phone/camera/object mount is)
- 3 Legs: 95A (what I used, but more flexible is fine) TPU filament, 0.2mm (or finer) layer height, 2 perimeters, 15% infill
- Lower & Upper Base: PLA/ABS/PETG (rigid filament, PLA works fine), 0.2mm (or finer) layer height, 2 perimeters, 15% infill
- Mount (for camera, phone, etc): Make this as strong/weak as you want (depends on the application! For my phone clamp, I just used the same settings as above)

Assembly is pretty simple:
1) Insert the Aluminum Wire into the TPU sleeves, and use wire cutters to slowly (twisting the wire cutters for each cut) sever the Aluminum Wire
2) Prepare the bottom base: insert the m5 nut into the underside of the base. Screw in a m5 screw (I think m5x16 will do, depends on your application!) from the bottom
3) Insert m3 nuts into their respective slots on the bottom base. Fasten each leg to the base
4) Slide in a m5 nut into the Upper Base (or mount your subject onto the m5 screw!)

##Final Product
And that's it! Works decently well, but be careful of the Aluminum Wire sliding around a lot!
![FlexPod](https://github.com/user-attachments/assets/4ab55020-e177-49e7-8927-8b7fe57a2cd8)
Access the project on Printables here: https://www.printables.com/model/1480173-flexpod-a-better-gorillapod-phone-tripod
Youtube video: https://youtube.com/shorts/_ZZmN3UGOKQ?feature=share
