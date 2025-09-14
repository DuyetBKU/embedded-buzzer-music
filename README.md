# 🎵 Arduino/ESP32 Buzzer – Senbonzakura

> **Play Japanese music with a buzzer on Arduino/ESP32**  
> This project plays the song **千本桜 (Senbonzakura)** through a passive buzzer, compatible with both Arduino and ESP32 boards.  
> You can try it directly on Wokwi without any physical hardware!

---

## 📹 Demo

[![Senbonzakura Buzzer Demo](https://img.youtube.com/vi/Mqps4anhz0Q/hqdefault.jpg)](https://www.youtube.com/watch?v=Mqps4anhz0Q)  
_(Original song on YouTube – this project recreates its melody)_

---

## 🌐 Try it on Wokwi

💻 **Click to run:** [Senbonzakura on Wokwi](https://wokwi.com/projects/438927676899597313)  
No download needed – just open the link and click **▶ Start Simulation**.

---

## 🛠️ Required Hardware (for real setup)

- **Arduino Uno**, Nano, or **ESP32**
- **Passive buzzer**
- Breadboard jumper wires

Sample wiring:  
| Buzzer Pin | Arduino/ESP32 Pin |
|------------|------------------|
| + (VCC) | GPIO 2 _(can be changed)_ |
| - (GND) | GND |

---

## 📄 Main Code

The `main.ino` file contains:

- **melody[]** array: note frequencies for Senbonzakura (defined in `pitches.h`)
- **noteDurations[]** array: note lengths (beats)
- `tone()` function to play notes
- Delay between notes to create pauses

---

## 🚀 How to run on real hardware

1. Open **Arduino IDE**
2. Select **Board**: Arduino Uno / ESP32
3. Select the correct **Port (COM5, COM8, ...)** 
4. Download the `pitches.h` file (included in the repo)
5. Upload the code to your board and enjoy the music 🎶

---

## 📚 References

- [Arduino tone() function](https://www.arduino.cc/reference/en/language/functions/advanced-io/tone/)
- [Wokwi Arduino Simulator](https://wokwi.com)

---

## ❤️ Why I made this

Because I heard this and felt it funny [Senbonzakura](https://www.youtube.com/watch?v=Mqps4anhz0Q) so I wanted to turn it into a **buzzer version** to both practice and share the joy with others.

---

© 2025 DuyetBKU — Made with C++ and a love for embedding.
