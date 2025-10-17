# 🎧 SimpleEQ – My Journey into Audio Plugin Development (JUCE + C++)
  
This is **SimpleEQ**, a small but meaningful project in my journey of learning **audio plugin development** using the [JUCE framework](https://juce.com/) and **C++**.  
I’m still learning the ropes of DSP and plugin architecture, so this project serves as both a **hands-on experiment** and a **learning log**.

---

## Why I Started This

I’ve always been fascinated by how plugins shape sound — from EQs and compressors to synths.  
I spend a lot of time producing music and experimenting with **VSTs** in **Reaper**, tweaking parameters and layering effects just to see how they change the tone.  

At some point, I realized I didn’t just want to use plugins — I wanted to **build my own**.  
Since I already love both **music production** and **coding**, learning to create audio plugins felt like the perfect intersection of the two.  

This project began as a small YouTube tutorial, but it’s turning into something much more personal — a hands-on way to understand how DSP and C++ actually shape the sound I hear every day.


---

##  What I’m Learning

- How **JUCE’s AudioProcessor** and **AudioProcessorEditor** classes interact  
- The concept of **parameter trees** with `AudioProcessorValueTreeState`  
- How **frequency bands** are isolated and controlled in a digital EQ  
- Managing **gain**, **cutoff frequencies**, and **filter types**  
- The process of building and exporting **VST3 plugins** for DAWs

---

##  Features (so far)

-  3-band EQ (Low, Mid, High)  
-  Real-time processing using JUCE’s DSP module  
-  Basic GUI for parameter control  
-  Standalone and VST3 build targets  

*(Still early-stage — I’m focusing more on understanding the DSP flow than the visuals right now.)*

---

##  Tech Stack

| Tool | Purpose |
|------|----------|
| **JUCE** | Core framework for plugin development |
| **C++17** | Main programming language |
| **Visual Studio / Projucer** | IDE and project management |
| **Git + GitHub** | Version control and documentation |
| **Reaper / FL Studio** | For testing the plugin |

---

##  Setup Instructions

1. Clone the repo:
   ```bash
   git clone https://github.com/Abhishekar-Vedangi/SimpleEQ.git
   cd SimpleEQ
