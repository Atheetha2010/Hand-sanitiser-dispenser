# SaniSpray 

Automatic hand sanitizer dispenser that activates a 12V pump motor every 2 seconds 
when a hand is detected, and stops immediately when the hand is removed. 
Built using a 555 timer in astable mode and IR sensor — no microcontroller, purely analog.

## ⚙️ How It Works
An IR sensor detects the presence of a hand. While the hand is detected, the 555 timer 
running in astable mode generates a continuous pulse every 2 seconds, driving a 12V 
pump motor to spray sanitizer. When the hand is removed, the IR sensor cuts the signal 
and the pump stops immediately.

No code. No microcontroller. Entirely analog circuit logic.

## 🔧 Components
| Component | Purpose |
|---|---|
| 555 Timer IC (astable) | Generates 2-second pulses to drive the pump |
| IR Sensor | Detects presence and removal of hand |
| Relay Module | Allows 555 timer to switch the 12V pump motor |
| 12V Pump Motor | Dispenses sanitizer spray |
| Custom PCB (KiCad) | Houses the full circuit |
## 📐 PCB Design
Custom PCB designed from scratch in **KiCad**.

![PCB Photo](pcb.jpg)

##  Built At
**Unschool Robotics Lab** — as part of an integrated IGCSE program.

##  Status
✅ Completed and assembled — January 2026
