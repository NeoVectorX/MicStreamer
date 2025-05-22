# 🎤 MicStreamer Full Setup Guide

Welcome to **MicStreamer**, the ultimate Vision Pro mic streaming solution. This guide walks you through setting up the app on your Vision Pro and pairing it with the Windows or MacOS Receiver.

---

## Setup on Vision Pro:

**Step 1: Launch Mic Streamer**
- Open the **Mic Streamer** app on your Apple Vision Pro.
- Enter your PC’s IP address in the **Target IP** field.
  - _Tip:_ On your PC, open Command Prompt and type `ipconfig`. Look for **IPv4 Address**.
- Toggle **Stream Microphone** to **ON**.

---

## Windows PC Version:

**Step 2: Install VB-Audio Virtual Cable**
1. Go to [vb-audio.com/Cable](https://vb-audio.com/Cable/) and download/install the **VB Audio Driver**.
2. Restart your PC after installation.
3. Extract the **MicStreamer-Windows-Receiver.zip** downloaded from here: [Releases](https://github.com/NeoVectorX/MicStreamer/releases).
4. Run MicStreamer.exe. **Note:** Windows Defender may popup a warning as the app is not signed. Click **More Info/Run Anyway** to launch the app.  
5. Click **Start Listening** to begin receiving audio.
6. The app will display **"Listening..."** and show incoming audio data when streaming starts.

**Step 4: Route Audio to VB-Audio Cable**
7. The app sends audio to your system’s **default playback device**.
8. Right-click the speaker icon in your Windows taskbar > **Sounds** > **Playback** tab.
9. Set **VB-Audio Virtual Cable** as your **Default Playback Device**.

---

## MacOS Version:
1. Go to [vb-audio.com/Cable](https://vb-audio.com/Cable/) to download and install the MacOS VB Audio Driver. Restart Mac.
2. **Download** the latest Mic Streamer MacOS Receiver from [Releases](https://github.com/NeoVectorX/MicStreamer/releases).
3. Connect to Virtual Display in the Apple Vision Pro. **(This step is important to be able to select the Vision Pro audio in the following steps)**
5. Open Discord or preferred voice chat app and select VB-Audio Virtual Cable as input device. Output set to Vision Pro (Your Vision Pro Device Name). 
6. Set Mac system sound setting to **Vision Pro** output. 
7. Run the Mac Receiver app and click Start Listening.
8. You're done! Check the [Guide.md](Guide.md) for additional tweaks/settings in Discord, etc.

---

## Configure Discord (or Any App):

**Set VB-Audio as Input**
- Open **Discord** > **User Settings** > **Voice & Video**.
- Under **Input Device**, select **VB-Audio Virtual Cable**.
- Turn **OFF** the following for best quality:
  - Echo Cancellation
  - Noise Reduction
  - Automatic Gain Control
- Under **Input Sensitivity**:
  - Disable **"Automatically determine input sensitivity"**.
  - Manually set the slider so your voice triggers green bars without cutting out.


---

## You Are Done! 
- Your Vision Pro microphone audio is now streaming into your Windows app and ready for Discord or any app of your choice!
- Windows Version: From now on you just open the app, click Start Listening, and Toggle Stream Microphone in the Vision Pro app. The app will save your settings such as IP address, etc.
- Mac Version: Due to the VisionOS design, you may need to select your Vision Pro Audio once connected in Virtual Display if it doesn't default to the Vision Pro. 


---

## FAQ / Tips:
---

### Use with Any App:
You're not limited to Discord!  
You can route your Vision Pro mic audio into any app that accepts audio input.  
Just set **VB-Audio Virtual Cable** as the **Input Device** in that app’s audio settings.

---

### Mini Mode - Floating Mute Button:
- Want to move the app out of the way but keep mic control handy?
- Tap **"Launch Floating Mute Button"** inside the app.
- This spawns a small, draggable mute/unmute button you can place anywhere in your space for quick access during gameplay or calls.
- A single tap Mutes the Mic audio (red). Tap it again to unmute. 
- A long press (hold) turns the icon (gray) and activates audio dimming based off the setting chosen in the Vision Pro MicStreamer app. This is designed to allow users to hold a conversation in the room without removing the headset while gaming. Release to return audio back to the previous state. 

---

### Wi-Fi Reminder:
- Your Vision Pro and PC must be on the **same Wi-Fi network** for low-latency streaming.

---

### No Audio? ☹️
- Ensure:
  - The **Mic Streamer Windows** app is running and **Start Listening** has been clicked.
  - Untoggle/Retoggle Microphone Streaming in app.
  - If you switch focus away from Moonlight to another app (or the Vision Pro home screen) and then return, the Mic Streamer may stop sending audio until you toggle the mic stream off and back on again. This is due to how the Vision Pro handles audio session interruptions and app focus changes. Retoggling the Mic Stream will fix it. 
  - **VB-Audio Virtual Cable** is the **Default Playback Device**.
  - Discord’s **Input Device** is set to **VB-Audio Virtual Cable**.
  - Make sure you don't have the Draggable Mute Button muted. 

---

### Voice Activity Detection (VAD):
- You can enable **VAD** in the Vision Pro app for auto-mute when silent.

---

### Gain Adjustment:
- Adjust the **Gain** in the Vision Pro app if your audio is too soft or too loud.

---

### Antivirus Warning?
- Some antivirus software may flag the Mic Streamer Windows Receiver App on first launch.
- This is a **false positive** due to the app’s custom, unsigned code.
- You can safely **allow** or **whitelist** the app in your antivirus settings.
- IF the app becomes popular, I will certainly get the code signed. 


