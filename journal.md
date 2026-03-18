# 🛠️ Project: Cartesian Gantry Slinger
**Made by:** @firesareba // simha saraswati  
**Repository:** [Cartesian-Gantry-Slinger](https://github.com/firesareba/Cartesian-Gantry-Slinger)  
**Total Time Invested:** 42 Hours

- [x] I have a 3D printer

---

### 📅 2/27 - 3/1 
**Time:** 8 Hrs

> **RESEARCH:** > Well, this time was just a lot lot lot lot lot of research. I was origianlly planning a flying gantry, then a weird thing where the toolhead alone drops down for the z, then I settled on this. The main purpose of having it like this is so the bed stays stationary, so tall or heavy prints arent messed up by sudden movements. In this research, i mainly used AI (ai helped a lot when making this printer), namely Gemini 3 Flash in Google AI Studio. Other resources include some videos, my favorite of which is this one: https://www.youtube.com/watch?v=yuAN5AzEWCg. Other useful resources are McMasterCarr (LIFESAVER)/

---

### 📅 3/9 
**Time:** 7 Hrs

I hopefully finished most of the Y axis. It uses belts as the drive with linear rails as guides. In this kind of printer it moves the entire XZ gantry across the Y axis instead of the bed. I might change the size of the bed (140mmx140mm) later if I have space.

<img width="836" height="575" alt="Screenshot 2026-03-09 at 2 01 20 PM" src="https://github.com/user-attachments/assets/1b65bdf6-ba68-4ae8-98aa-7ea68adfaaf1" />

---

### 📅 3/12 
**Time:** 8 Hrs

Today I finished the Z axis, which basically uses lead screws with 2 nema 17 pancakes moving it up and down. I first designed a custom mount which goes onto the MGN12H of the Y axis and attatches to the belt with the loop and ziptie method (I was originally planning to use the more simple passenger belt but apparently that sucks), even then, its technically compatible with both methods so yeah. It has nema 17 pancake and a 2020 extrusion on it (IDK if i will buy a machined one or a printed one, whichever is cheaper). I used lead screws witha  flange nut to hold the x axis while having it all connected to MGN12H rails (i use a lot of these rails in this project). I made this journal AFTER I also finished part of the x axis so thats why its like that. U can see how it moves in the mp4 video in the repo.

<img width="836" height="836" alt="Screenshot 2026-03-09 at 2 01 20 PM" src="Screenshot 2026-03-14 222817.png" />

---

### 📅 3/14 
**Time:** 4 Hrs

Ok, today was the easiest, the X axis was really easy, i mean its close to done, i still need the toolhead stuff. All i did was design a mount for the flange nut and the MGN12H that goes up and down with the z axis. Then i put another MGN12H rail (i promise its the last one) across it bridging the 2 mounts together for a unified x axis (im using the rail as a structure to reduce weight). Then i mounted a nema 17 pancake motor to one end of the axis and a idler pulley to the other end creating a belt system, which when i design toolhead, will be another loop and fasten belt drive. You can see how it looks on the picture before, and i will provide a close look in a video after when the whole printer is finished,

---

### 📅 3/15 
**Time:** 7 Hrs

Today was by far the most PAINFUL DAY out of all of them.  The one where i designed the toolhead. GOSH the amount of BRAINCELLS i lost doing this was insane. The gist of it is that a plate connects to the belt for movement, which is connected the the BMG extruder, which also has a Nema 17 Pancake attatched to it.
Then i thought i was done, then i realized i needed the fucking blower fan (OK) but also the bed leveling sensor. the amount of braincells i lost for this single thing was insane, i never want to do ts again. the mounting was so annoying. But ay, atleast this is finished (hopefully lol). Now I have to do everything else, and i will be done with design.

<img width="374" height="347" alt="image" src="https://github.com/user-attachments/assets/2dc52ea8-b3fd-42c8-8699-3882484a75d4" />

---

### 📅 3/16-3/17 
**Time:** 8 Hours

Yesterday and today was pretty basic, although it was a lot of work. Basically what i worked on is mounting components like bed, SKR Mini, and worked on the bom. Overall it was pretty simple. The reason it was much simpler is because the build plate is stationary, meaning I can use a really basic mounting system and done need a complex one, (I used a screw clamp). The biggest pain was the BOM, i did NOT anticipate how expensive MGN12h rails are :_(, I had to cost cut in many ways, including replacing some extrusions with printed ones, using a old latpop to run klipper instead of a pi zero, and other measures, but it all worked out in the end :D! Hopefully it gets aproved and I can go to RMRRF!!!! :D :D :D :D :D.

<img width="1808" height="920" alt="Screenshot 2026-03-17 221811" src="https://github.com/user-attachments/assets/d79b2795-3e1d-4387-8c42-a3e848bca8fa" />
<img width="1918" height="1187" alt="Screenshot 2026-03-17 221807" src="https://github.com/user-attachments/assets/f0a60c19-e1d7-4f6e-874a-a4c918833c80" />
<img width="782" height="766" alt="Screenshot 2026-03-17 221758" src="https://github.com/user-attachments/assets/77ed61a2-cda-4ccc-b7d8-4918acfe0573" />
<img width="1114" height="1028" alt="Screenshot 2026-03-17 221752" src="https://github.com/user-attachments/assets/f23466dc-427b-42e2-881f-62b17f4a9937" />
<img width="964" height="992" alt="Screenshot 2026-03-17 221741" src="https://github.com/user-attachments/assets/77b9c1b6-eb7a-4bd4-a1a8-f3981ecb0634" />
<img width="863" height="1037" alt="Screenshot 2026-03-17 221734" src="https://github.com/user-attachments/assets/8782b1b5-3aad-4b84-94bd-42836262ebb2" />
<img width="374" height="347" alt="Screenshot 2026-03-16 163949" src="https://github.com/user-attachments/assets/cec6a7a4-d4f4-4f11-bb39-d3549cd3cde6" />
