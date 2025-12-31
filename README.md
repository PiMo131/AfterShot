# AfterShot — Free After-Shot Review App (Web Test Version)

**AfterShot** is a **free** after-shot review app that automatically saves video around a shot.  
Instead of recording everything, it keeps only the most relevant moment: **before and after the shot**.

👉 **Test it here (no install needed):**  
**https://pimo131.github.io/AfterShot/**

---

## User Manual (Quick Start)

The phone must be mounted on the rifle with this kind of mounting:
<img width="345" height="326" alt="image" src="https://github.com/user-attachments/assets/4cbd47b2-d40b-4748-b04b-3d2b43cd02fd" />




### What you need
- A smartphone (recommended: **Android + Chrome**)
- Camera and microphone permissions enabled
- Enough battery (screen stays on during use)

---

### Step-by-step usage

#### 1. Open the app
Open this link in your mobile browser:

👉 **https://pimo131.github.io/AfterShot/**

For best results:
- Use **Chrome on Android**
- Rotate your phone to **landscape mode**

---

<img width="1893" height="838" alt="image" src="https://github.com/user-attachments/assets/1e3252f4-571f-45c8-8919-f19b15695373" />

#### 2. Start the app
Tap **Start** at the bottom of the screen.

The app will:
- Ask permission for **camera** and **microphone**
- Try to switch to **full screen**
- Keep the **screen awake**

---

#### 3. Calibrate (important!)
Hold your device in your normal **ready / firing position**.

Tap **Calibrate**.

This tells the app what “normal” looks like, so it can detect when the device is pointed downward later.

---

#### 4. Record automatically
Once started:

- The camera runs in the background
- The app keeps a short **rolling buffer** of video
- When a **shot-like sound** is detected:
  - Video **before** and **after** the shot is saved automatically

You do **not** need to press record for each shot.

---

#### 5. Muzzle-down standby
If the device is pointed downward for a while:
- Camera and microphone automatically **stop**
- This saves power and avoids unnecessary recording

When you raise the device again:
- Recording **resumes automatically**

---

#### 6. View and download clips
1. Open **Menu**
2. Scroll to **Downloads**
3. Tap a clip to save it to your device

Clips are saved as **WebM video files**.

---

## Settings (Menu)

Open **Menu** (top right) to adjust behavior.

### Common settings
- **Pre-roll (X seconds)**  
  How much video is saved *before* the shot (default: 10 s)
- **Post-roll (Y seconds)**  
  How much video is saved *after* the shot (default: 5 s)

### Shot detection
- **Peak threshold** – how loud the sound must be
- **Impulse score** – helps distinguish sharp shots from noise
- **Cooldown** – prevents double triggers

### Standby (muzzle-down)
- **Down threshold (degrees)** – how far downward the device must point
- **Down duration** – how long it must stay down before standby
- **Resume threshold** – angle for resuming recording
- **Invert pitch** – use if detection works the wrong way around

---

## Important limitations (Web version)

Because AfterShot runs **inside a browser**, there are some unavoidable limitations:

- 🔆 **The screen stays on** while recording  
- ⏸️ The browser must stay **open and active**
- 🔋 Power consumption is higher than a native app
- 📱 Behavior may differ between devices and browsers
- 🍏 iOS Safari has stricter limits than Android Chrome

This test version assumes:
- The page stays open
- The screen remains on
- The browser stays in the foreground

---

## Why a web version?

This web version exists to:
- Test the concept quickly
- Get real-world feedback
- Improve shot detection and usability
- Avoid mandatory installation during early testing

---

## Future development

A future **native Android / iOS app** may add:
- True background recording
- Screen-off or dark-screen modes
- Better battery management
- Higher reliability across devices
- More advanced sensor fusion

---

## Privacy

- Video and audio stay on your device
- No uploads or cloud storage are required
- Clips are only saved when triggered

---

## Disclaimer

AfterShot is intended for **after-shot review and training purposes** only.  
Always follow local laws, range rules, and privacy regulations when recording.

---

## Feedback

This is a testing version.  
Feedback, bug reports, and suggestions are welcome via GitHub Issues.
