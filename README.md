# 🔥 Project 1 — VR Torch Interaction (Unreal Engine 5.5.4)

A Blueprint-driven VR torch built in the UE5 VR Template.
Includes grabbing, lighting, VFX, sound, and VR-ready interaction logic.

---

## 🎯 Features

- Grab-ready torch using the VR Template GrabComponent
- Dynamic point light with warm color for cave/horror atmospheres
- Niagara flame effect positioned and scaled for VR use
- Physics-enabled mesh for realistic weight and motion
- Custom pivot + grab point alignment for natural VR hand placement
- Torch sound cue and customized lighting color

---

## 📦 Assets Used

- **Medieval Torch (Free)** — torch mesh
- **M5 VFX Vol.2 Fire & Flames (Free)** — Niagara flame systems

Both assets import cleanly into the VR Template.

---

## 🛠️ Blueprint Setup

### **BP_Torch**

- Static Mesh (scaled for VR)
- Simulate Physics enabled
- GrabComponent set to _Snap_
- Point Light positioned at torch head
- Niagara flame system aligned with light
- Sound Cue added for torch ambience

Pivot and GrabComponent are positioned for proper hand placement during VR grab.

---

## 🎮 In-Game Use

- Place _BP_Torch_ in the VR map
- Grab using the default VR Template grab logic
- Light, flame VFX, and sound all function in VR Preview

---
