# Cartesian-Gantry-Slinger
**Made by:** @firesareba // simha saraswati  
**Repository:** https://github.com/firesareba/Cartesian-Gantry-Slinger  
**Total hours so far:** 42

### Overview
This is a custom Cartesian 3D printer designed as a Gantry Slinger. The main purpose of this design is to keep the bed stationary so tall or heavy prints arent messed up by sudden movements. Instead of the bed moving, the entire XZ gantry moves across the Y axis.

### Technical Specifications
* **Motion System:** The printer uses MGN12H linear rails for all axes. The Y axis moves the entire gantry using a belt drive.
* **Z-Axis:** Uses lead screws with dual Nema 17 pancake motors. It features a custom mount that attaches to the Y-axis MGN12H using a loop and ziptie method for the belts.
* **X-Axis:** Uses an MGN12H rail as the actual structure to reduce weight. It features a Nema 17 pancake motor and an idler pulley for a unified belt system.
* **Toolhead:** Features a BMG extruder with a Nema 17 pancake. Designing the mounting for the blower fan and bed leveling sensor was by far the most PAINFUL part of the design process.
* **Electronics:** SKR Mini running Klipper. To save on costs, I’m using an old laptop to run Klipper instead of a Pi Zero.

### BOM & Cost Optimization
MGN12H rails are extremely expensive, so I had to cost cut in several areas to stay on budget:
* Replaced some 2020 extrusions with printed parts.
* Used a simple screw clamp mounting system for the stationary bed.
* Utilized an old laptop for the firmware host.

### Design Gallery
<img width="1808" height="920" alt="Full Assembly View" src="https://github.com/user-attachments/assets/d79b2795-3e1d-4387-8c42-a3e848bca8fa" />

| Component Details | Toolhead & X-Axis |
|---|---|
| <img src="https://github.com/user-attachments/assets/f0a60c19-e1d7-4f6e-874a-a4c918833c80" width="450"> | <img src="https://github.com/user-attachments/assets/2dc52ea8-b3fd-42c8-8699-3882484a75d4" width="450"> |
| <img src="https://github.com/user-attachments/assets/77ed61a2-cda-4ccc-b7d8-4918acfe0573" width="450"> | <img src="https://github.com/user-attachments/assets/f23466dc-427b-42e2-881f-62b17f4a9937" width="450"> |
| <img src="https://github.com/user-attachments/assets/77b9c1b6-eb7a-4bd4-a1a8-f3981ecb0634" width="450"> | <img src="https://github.com/user-attachments/assets/8782b1b5-3aad-4b84-94bd-42836262ebb2" width="450"> |

CAD can be viewed here https://cad.onshape.com/documents/4b7d20fc78499882d952db83/w/426ea4e6b1dd389c75ce2c2f/e/88c5687be45517fc3e9cc648?renderMode=0&uiState=69babc656960cf6b0f19f722 or the STEP File

### Progress
- [x] Initial Research (Settled on Gantry Slinger over Flying Gantry)
- [x] Y-Axis Design & XZ Gantry movement
- [x] Z-Axis lead screw integration
- [x] X-Axis belt system
- [x] Toolhead assembly (Extruder, Fan, Sensor)
- [x] BOM cost reduction
- [ ] Final Assembly
- [ ] RMRRF Submission

---
**Resources:** McMasterCarr (LIFESAVER), Gemini 3 Flash (AI helped a lot making this printer), and this video: https://www.youtube.com/watch?v=yuAN5AzEWCg
