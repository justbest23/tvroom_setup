# tvroom_setup

A guide created after extensive conversation with ChatGPT. Uses my existing hardware plus a new amp. This is to remind me of my setup which I will now forget about for a few years.



# Denon + Marantz Home Theatre Wiring Guide

**Setup: 7.1.4 + Outdoor Speakers (Stereo)**  
**Master AVR: Denon AVR-X3800H**  
**Slave Amp: Marantz SR5003**  

---

## 🧩 Denon AVR-X3800H Connections

### ▶️ 7.1 Inside Speakers
- Front L/R → Speaker terminals  
- Centre → Speaker terminal  
- Surround L/R → Speaker terminals  
- Surround Back L/R → Speaker terminals  
- Subwoofer → RCA Subwoofer Out → Subwoofer

### ▶️ Height Channels (via Marantz)
- Height 1 L/R Pre-Out → RCA → Marantz **CD Input**  
- Height 2 L/R Pre-Out → RCA → Marantz **TAPE IN**

### ▶️ Outdoor Speakers
- Assign **Height Amp Channels** to **Zone 2**
- Outdoor L/R speakers → Height assignable speaker terminals  
- Sub outside (optional) → RCA pre-out (use Zone 2 Sub Pre-Out if available, or split main sub out using RCA Y splitter)

---

## 🎚 Marantz SR5003 Connections

### ▶️ Input Routing
- CD Input (RCA) → Connected from Denon Height 1 Pre-Out  
- TAPE IN (RCA) → Connected from Denon Height 2 Pre-Out

### ▶️ Zone Assignments
- **Zone A (Front A)** → Source: CD → Powers Height 1 Speakers  
- **Zone B (Front B)** → Source: TAPE IN → Powers Height 2 Speakers  

### ▶️ Speaker Terminals Used
- **Front A** → Height 1 L/R  
- **Front B** → Height 2 L/R  

---

## 🧠 Tips & Notes

- Set both **Zone A and Zone B active** on the Marantz.  
- **Volume control**: Either fix the volume on the Marantz or manually calibrate it to match the Denon’s level.  
- You must **turn on the Marantz manually or with automation** — it does **not have a 12V trigger input**. Use a smart plug or IR blaster if needed.  
- On the **Denon**, assign the Height pre-outs correctly in the speaker settings (7.1.4 layout).  
- On the **Denon**, assign Zone 2 to use the internal amp if powering outdoor speakers directly.  

---

## ✅ Summary Table

| Function              | From                  | To (Device/Input)      | To (Output)               | Powers                            |
|-----------------------|-----------------------|-------------------------|----------------------------|------------------------------------|
| Front / Centre / Surround / Sub | Denon Speaker / RCA Out | —                       | —                          | 7.1 speakers inside                |
| Height 1              | Denon Height 1 Pre-Out | Marantz CD IN          | Front A Speaker Terminals | Height 1 L/R (inside)              |
| Height 2              | Denon Height 2 Pre-Out | Marantz TAPE IN        | Front B Speaker Terminals | Height 2 L/R (inside)              |
| Outdoor Stereo        | Denon assignable amp  | —                       | Height assignable outputs | Stereo speakers (outside)         |
| Outdoor Subwoofer     | Denon Sub Out (split) | —                       | RCA to powered sub        | Optional external sub (outside)   |
