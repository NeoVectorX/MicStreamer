## Mic Streamer
Mic Streamer is a Vision Pro app that streams high-quality microphone audio over your local network in real time. Paired with the Windows or MacOS audio receiver, MicStreamer lets Vision Pro users enjoy low-latency voice capture for gaming, voice chat, and more—directly from their headset.



## 🔥 Features
- Low-latency audio reception
- Mini Mode with a tactical floating mute button
- Game Audio Dimming feature to allow real-world conversations (Feature currently unavailable on MacOs)
- 16-bit stereo 48kHz PCM playback
- Compatible with VB-Audio Virtual Cable for Discord & game streaming

## 🖥️ Windows & MacOS 

![MicStreamer Windows](https://github.com/NeoVectorX/MicStreamer/blob/main/Micstreamer-Windows.jpg)

---

## 🚀 Quick Start Guide

Note: Read the [Guide.md](Guide.md) for full in-depth instructions

### Vision Pro: 

1. Install the Mic Streamer on Apple Vision Pro
2. Type in your windows IP address
3. Toggle Stream Microphone

### Windows: 
1. Go to [vb-audio.com/Cable](https://vb-audio.com/Cable/) to download and install the VB Audio Driver. Restart PC.
2. Right-click the speaker icon in your Windows taskbar > Sounds > Playback tab and set VB-Audio Virtual Cable as your Default Playback Device.
3. **Download** the latest Mic Streamer Windows Receiver from [Releases](https://github.com/NeoVectorX/MicStreamer/releases).
4. Run **MicReceiver.exe** and click to Start Listening
5. Open Discord or preferred voice chat app and select VB-Audio Virtual Cable as input device. 
6. You're done! Check the [Guide.md](Guide.md) for additional tweaks/settings in Discord, etc.

### MacOS:
1. Go to [vb-audio.com/Cable](https://vb-audio.com/Cable/) to download and install the MacOS VB Audio Driver. Restart Mac.
2. **Download** the latest Mic Streamer MacOS Receiver from [Releases](https://github.com/NeoVectorX/MicStreamer/releases).
3. Connect to Virtual Display in the Apple Vision Pro. **(This step is important to be able to select the Vision Pro audio in the following steps)**
5. Open Discord or preferred voice chat app and select VB-Audio Virtual Cable as input device. Output set to Vision Pro (Your Vision Pro Device Name). 
6. Set Mac system sound setting to **Vision Pro** output. 
7. Run the Mac Receiver app and click Start Listening.
8. You're done! Check the [Guide.md](Guide.md) for additional tweaks/settings in Discord, etc.

### Mini Mode - Floating Mute Button:
Want to move the app out of the way but keep mic control handy?
Tap "Launch Floating Mute Button" inside the app.
This spawns a small, draggable mute/unmute button you can place closeby for quick access during gameplay or calls. No need to pinch to click. 
A single quick tap with your finger Mutes the Mic audio (red). Tap it again to unmute.
A long press (hold) turns the icon (gray) and activates audio dimming based off the setting chosen in the Vision Pro MicStreamer app. This is designed to allow users to hold a conversation in the room without removing the headset while gaming. Release to return audio back to the previous state.



### ⚠️ Heads-Up: Unsigned App Notice

The MicStreamer Windows Receiver is currently **not digitally signed**, so you may see a Windows SmartScreen warning the first time you run it.  Click More Info -> Run Anyway to launch. This is normal for unsigned apps from independent developers. The EXE is 100% safe and open-source — feel free to inspect the code or build it yourself. 

---



## 📖 Full Setup Guide & Tips

For a full setup guide, including Vision Pro app pairing and troubleshooting, check out [Guide.md](Guide.md).

---


## 🛠️ Troubleshooting
  - Ensure the **Mic Streamer Windows** app is running and **Start Listening** has been clicked.
  - Untoggle/Retoggle Microphone Streaming in app.
  - If you switch focus away from Moonlight to another app (or the Vision Pro home screen) and then return, the Mic Streamer may stop sending audio until you toggle the mic stream off and back on again. This is due to how the Vision Pro handles audio session interruptions and app focus changes. Retoggling the Mic Stream will fix it. 
  - **VB-Audio Virtual Cable** is the **Default Playback Device**.
  - Discord’s **Input Device** is set to **VB-Audio Virtual Cable**.
  - Ensure the Mute Button isn't enabled.
  - The VAD (Voice Activity Detection) setting cuts off the voice stream to reduce latency even further. Disable to keep a constant voice stream. 


---

## 🔧 Requirements
- Windows 10 or newer, or MacOS 13 or newer
- .NET Framework 4.8+
- VB-Audio Virtual Cable Driver

  -- This code is provided for personal use only. Redistribution or modification is not permitted without permission. --

---

## 💬 Feedback

Still have issues of have feedback? hit me up me on [Reddit](https://www.reddit.com/user/Kengine/) or Open an [Issue](https://github.com/NeoVectorX/MicStreamer/issues). Make to check the full setup guide as there's tips and more indepth setup information. If you like this app please take a second to give me a ⭐ at the top of the Github!

---

## 🙌 Thanks

To Samantha and Daniel for brainstorming with me about Mic Streamer, and to CrowKing63, Ms Noah, Notto, Tifthir, and Minel for testing the app!
