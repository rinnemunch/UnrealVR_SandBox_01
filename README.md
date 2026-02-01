# 🔥 Project 1 – VR Torch Interaction (UE5)
**[Medium Guide](https://medium.com/@fulton_shaun/how-to-create-a-torch-in-vr-using-unreal-engine-5-256f9f1bbc84)** • **[YouTube Tutorial](https://www.youtube.com/watch?v=TWaClKwhcII)**

This project builds a **Blueprint-driven VR torch** inside **Unreal Engine 5.5.4**, using the VR Template’s built-in grab system.
The torch includes physics, hand-snap interaction, Niagara flame effects, warm lighting, and optional sound — a clean, reusable VR mechanic for any first-person VR project.

---

## 🖼️ Preview

![VR Torch Demo](Media/Torch.gif)

---

## 🧱 Features

- **BP_Torch actor** created as the pickup object
- **Static Mesh setup**
  - Medieval Torch mesh imported from Fab
  - Scaled for VR (0.01 on all axes)
  - Simulate Physics enabled for natural weight
- **VR GrabComponent**
  - Grab Type: Snap
  - Aligned to the bottom of the handle
  - Rotation corrected (X = 180°) for natural hand orientation
- **Lighting**
  - Point Light added inside the torch head
  - Intensity set to 1000
  - Warm color applied for realistic fire glow
- **Niagara VFX**
  - Flame system attached (`3_Nblowingfire_fwd_pt` example)
  - Positioned to match the light (Z alignment)
  - Scaled for VR readability (≈10 on all axes)
- **Pivot + Grab Point Setup**
  - Pivot moved to bottom of torch using Pivot Offset
  - GrabComponent aligned exactly at the holding point
- **Sound Integration**
  - Looping torch fire sound cue added (optional)
  - Volume and attenuation tuned for VR presence
- **In-Scene Testing**
  - BP_Torch placed in VR map
  - Lighting previewed with Ctrl + L
  - VR Preview tested with full grab, flame, and light effects

---

## 🚀 Result

Press **Play (VR Preview)**, reach out, and grab the torch.
It snaps cleanly into your hand with:

- Natural pivot-based alignment
- Warm dynamic lighting
- Niagara flame effects
- Optional fire sound

A polished, VR-ready torch interaction system you can drop into any VR project.

---
