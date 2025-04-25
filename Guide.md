# 🎛️ MicStreamer Full Setup Guide

Welcome to **MicStreamer**, the ultimate Vision Pro mic streaming solution. This guide walks you through setting up the app on your Vision Pro and pairing it with the Windows Receiver.

---

## 🥽 Vision Pro Setup:
1. **Install MicStreamer** on your Vision Pro from TestFlight.
2. Open the app and grant microphone permissions when prompted.
3. Enter your Windows PC’s local IP address (e.g., `192.168.1.100`).
4. Toggle **Stream Microphone** to **ON**.
5. You should now see your mic level bar animate when speaking.

### Optional Settings:
- **Voice Activity Detection (VAD):** Auto-mute when silent.
- **Gain Presets:** Adjust mic sensitivity to Low / Medium / High.
- **Launch Floating Mute Button:** Quick access to mute/unmute while streaming.

---

## 🖥️ Windows Receiver Setup:
1. Download and run **MicStreamerWindows.exe**.
2. Press **Start Listening**.
3. You’ll hear your Vision Pro mic streamed in real time.
4. (Optional) Change output to **VB-Audio Virtual Cable** to route audio into apps like Discord:
    - Set MicStreamer output to **Cable Input**.
    - Set Discord’s input to **Cable Output**.

---

## ⚙️ Tips for Best Performance:
- Use a **wired network** or strong **WiFi 5/6** connection.
- Ensure both Vision Pro and PC are on the **same local network**.
- Recommended audio format: **16-bit, Stereo, 48kHz** on Windows sound settings.
- If using VB-Cable, make sure its settings also match **16-bit, 48kHz**.

---

## 🔧 Troubleshooting:
- **No Sound?**
  - Check that your PC’s firewall allows UDP on port **9999**.
  - Verify the Vision Pro has the **correct IP address** entered.
  - Confirm **MicStreamerWindows** is set to **Start Listening**.
- **Distorted or Chipmunk Audio?**
  - Check that **Windows audio settings** (including VB-Cable if used) are set to **16-bit, 48kHz**.
- **High Latency?**
  - Try switching to a wired Ethernet connection for the PC.

---

## 🎮 Pro Tip:
You can game on Vision Pro with **Moonlight** while using **MicStreamer** for live voice chat through Discord on your PC—without needing a separate headset!

---

## 🤝 Thank You for Using MicStreamer!
Got feedback? Open an issue on GitHub or drop us a message.
