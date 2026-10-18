# merbl - straw hat marble run 🏴‍☠️

hii!! this is my custom 3d-printed marble race course made for the hack club merbl grant! i cadded the entire thing from scratch in onshape. it took me way too long and i almost lost my sanity trying to align and rotate everything at 3am, but we finally got it done and fitting completely inside the build plate haha.

---

## what is this?
its a gravity-powered marble track designed for an 8mm marble. the marble drops down a banked swooping track, shoots into a vortex funnel, spins around a few times and drops right on top of a custom luffy straw hat jolly roger base plate!

everything is arranged vertically so it stays compact and fits inside the standard 150x150 mm printer footprint.

---
## Screenshots

![Merbl CAD Screenshot](Screenshot%20from%202026-10-19%2004-39-22.png)

## the parts

### 1. straw hat base plate
* **size:** 150 x 150 x 3 mm
* drew the base outline and extruded it up, then imported and extruded the straw hat pirate logo on top of it. this acts as both the bottom foundation and the finish area where the marble rolls out.

### 2. track 1 - "gomu whip"
* **inner diameter:** 9mm (gives 1mm clearance for the 8mm marble so it doesnt get stuck)
* **outer diameter:** 14mm (2.5mm wall thickness)
* made an angled plane (slanted down so gravity actually pulls the ball), drew the path with lines and smooth fillet curves, and swept the 2d u-channel track profile along it. 
* it banks the marble into an s-curve to control its speed before dropping it into the funnel.

### 3. custom track - "black hole" funnel
* **outer diameter:** around 75mm dish
* **drop spout:** 10mm inner hole (5mm radius from center axis + 2.5mm wall thickness)
* sketched half of the funnel cross-section with an angled entry ramp, offset the wall thickness, and used the **revolve** tool 360 degrees around the center axis. 
* the track dumps the marble right into the outer bowl so it orbits around the drain hole before plunging out the bottom.

### 4. the marble
* modeled an 8mm sphere by sketching an 8mm circle on a plane, cutting it with a center line, and revolving the semi-circle. (though in real life an 8mm steel ball bearing rolls way smoother than printed plastic).

---

## cad tools & operations used in onshape
* **sketches & constraints:** dimension tool, coincident, horizontal/vertical, tangents, fillets, and equals.
* **angled reference planes:** created line-angle planes to give the tracks downward slopes.
* **sweep:** swept the 2.5mm thick u-channel profile along the 3d composite curve.
* **revolve:** revolved the funnel cross-section and the marble sphere around center axes.
* **transforms:** used `translate by xyz` heavily to stack all the floating parts vertically above each other and make sure everything stays inside the 150x150mm yellow base area.

---

## 3d printing & slicing notes
* **supports:** tree supports / organic supports are MUST. the tracks hover in mid-air over the base, so slicer tree supports will grow up from the base plate to hold the tracks during printing.
* **print orientation:** print flat with the base sitting on the bed.
* **recommended material:** standard pla (or 9600 resin if ordering from a service like jlc3dp for super smooth track surface).

---

## links & files
* **onshape document:** https://cad.onshape.com/documents/ac52588e4772ac24bda94688/w/fd6abf1c60b54b968ae4d34f/e/f29a6cca8404a38cbf456f0e
* **cad export files:** `Merbl.stl` (for 3d printing) and `Merbl.step` (for universal cad editing) are saved in this repo.

---

## Personal Experence
Oh hi !! i think that i was too much formal up !!
So well tbh JUST EVERYTHING BROKE AND I WASTED LOT'S OF HRS AND IN THE END ENEDED UP WITH JUST A TRACK FUNNEL AND MY BASE !!!!!! Uh i wasted lots of time !! :C but really it was not a waste :D since it taught me the CAD onshape for the first time yk i am 13 and i opened the openshape for the first time (My first cad was kicad which i opened for the week 1) but uh i lost the formating really above i formated really well but below uh yeah whatever 
so first of all i waked up all night today so i am sleepy if this readme doesn't apper good or there is any error just inform me i will eidt it (I have made time laspes of everything too !!! tho i named them like a boring old man !!!)