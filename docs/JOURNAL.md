# Development Log - Elusive Smart Glasses

## Date: June 11th, 2026

I realized that I could use Lapse so I don't need to continue this Journal.md
Also saves me the hassle of timing myself when I start and end on my phone Yay.



## Date: June 10th, 2026
**Time Spent:** 1 hour 14 minutes

**What I did:**
- I finished compiling the list of components that I'll be using. I researched the MC3416 as I'm unable to find the corresponding component of MC6470 in LCSC.

**Stuck on:**
- Nothing so far

**Tomorrow's Plans:**
- (blank)

**Concurrent Plans:**
- Elusive will have recording features. Elusive will have an AI that will be able to respond to the wearer in real-time using the microphone. Elusive will be able have a HUD that showcases gaming features such as a minimap, quests, stats etc.

---

## Date: June 9th, 2026
**Time Spent:** 1 hour 1 minute

**What I did:**
- I started to compile a list of all the components that I'll use in Elusive. I began with finding the corresponding LCSC components so I can easily get their footprint and pinout diagram in KiCad by using the easyeda2kicad github thingabob.

**Stuck on:**
- Deciding what components and how extensive I want Elusive to be. Do I want Elusive to have recording capabilities?
- Nothing so far

**Tomorrow's Plans:**
- Finish compiling the list of components that I'll be using
- I need to research the MC3416 as I'm unable to find the corresponding component of MC6470 in LCSC.

---

## Date: June 9th, 2026
**Time Spent:** 1 hour

**What I did:**
- I studied what Frame can do. I researched about 8Bit YCbCr. I researched more about the features of Frame and what I would want Elusive to actually be. I feel like I want Elusive to be the smart glasses that gamify the real world. That means Elusive needs to have a HUD along with a method of interacting with the HUD on the glasses. So the two features of Elusive will simply be a micro oled along with a method of interacting with the HUD. The aim of Elusive is to be easily customizable and easily made by anyone in the world with access to the repo. Elusive is smart glasses that turn the real world into a game. I am researching the schematics of the Frame. Mainly the MCU of the Frame(nRF52840) so far.

**What I learned:**
- The Frame has generative AI
- The Frame has an IMU that has an accelerometer along with a e-compass.
- The Frame uses the IMU to detect Touch that is used to navigate and select UI elements within the glasses.
- The Frame has a camera and microphone, allowing for the recording of videos
- I learned about FPGA along with Verilog and VHDL.
- The Bluetooth MCU in the Frame feeds clock and data directly into the display with H8 and H7.

**Stuck on:**
- Nothing so far.

**Tomorrow's Plans:**
- I need to learn about what all the pins on this Bluetooth MCU mean and how I can use them.
- I need to learn about how the IMU feeds into the Bluetooth MCU.
- I need to pick and model the donor frame that will be Elusive's Frame
- I need to look for frames with thick bridge in order to house the P

---

## Date: June 8th, 2026
**Time Spent:** 1 hour 1 minute

**What I did:**
- I began researching how the smart glasses of Brilliant Labs worked. Brilliant Lab's Frame is open sourced so I hope to learn everything on how to build Elusive from them. Or gain some inspiration/guidance on how to do so. I looked at the diagrams of the Frame and the Hardware that was used in the Frame. I need to research on what glasses frame I will use.

**What I learned:**
- I learned about the mechanism that Brilliant Labs' Frame glasses worked in displaying stuff for the user to see. The micro OLED shines on a optical prism that reflects it back onto the eye.
- I learned that the size/spacing between the two lens, the Bridge is where the PCB of the smart glasses should be.
- When deciding on the type of frame glasses, the bridge spacing should be the determing factor and then aesthetic afterwards.

**Stuck on:**
- Nothing so far.

**Tomorrow's Plans:**
- Learn what features I want the smart glasses to have.