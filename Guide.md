# 🎤 MicStreamer Full Setup Guide

Welcome to **MicStreamer**, the ultimate Vision Pro mic streaming solution. This guide walks you through setting up the app on your Vision Pro and pairing it with the Windows Receiver.

---

## 1. Setup on Vision Pro:

**Step 1: Launch Mic Streamer**
- Open the **Mic Streamer** app on your Apple Vision Pro.
- Enter your PC’s IP address in the **Target IP** field.
  - _Tip:_ On your PC, open Command Prompt and type `ipconfig`. Look for **IPv4 Address**.
- Toggle **Stream Microphone** to **ON**.

---

## 2. Setup on Windows PC:

**Step 2: Install VB-Audio Virtual Cable**
- Go to [vb-audio.com/Cable](https://vb-audio.com/Cable/) and download/install the **VB Audio Driver**.
- Restart your PC after installation.

**Step 3: Launch the Windows Receiver App downloaded here from Github** 
- Open the **Mic Streamer Receiver** app on your PC.
- Click **Start Listening** to begin receiving audio.
- The app will display **"Listening..."** and show incoming audio data when streaming starts.

**Step 4: Route Audio to VB-Audio Cable**
- The app sends audio to your system’s **default playback device**.
- To ensure proper routing:
  - Right-click the speaker icon in your Windows taskbar > **Sounds** > **Playback** tab.
  - Set **VB-Audio Virtual Cable** as your **Default Playback Device**.

---

## 3. Configure Discord (or Any App):

**Step 5: Set VB-Audio as Input**
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

## 4. You Are Done! 
- Your Vision Pro microphone audio is now streaming into your Windows app and ready for Discord or any app of your choice!

---

## FAQ / Tips:
---

### Use with Any App:
You're not limited to Discord!  
You can route your Vision Pro mic audio into any app that accepts audio input.  
Just set **VB-Audio Virtual Cable** as the **Input Device** in that app’s audio settings.

---

### Floating Mute Button:
- Want to move the app out of the way but keep mic control handy?
- Tap **"Launch Floating Mute Button"** inside the app.
- This spawns a small, draggable mute/unmute button you can place anywhere in your space for quick access during gameplay or calls.

---

### Wi-Fi Reminder:
- Your Vision Pro and PC must be on the **same Wi-Fi network** for low-latency streaming.

---

### No Audio? ☹️
- Ensure:
  - The **Mic Streamer Windows** app is running and **Start Listening** has been clicked.
  - Untoggle/Retoggle Microphone Streaming in app. 
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


