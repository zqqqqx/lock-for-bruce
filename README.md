# lock-for-bruce  
PIN / Lockscreen Script for Bruce Firmware

## Important Notice
- JavaScript interpreted files are **currently NOT supported**. Support will be added in the **next** Bruce firmware update.
- The lockscreen **does not open automatically on device boot yet**.

---

## Features
- Randomized (shuffled) numpad on each unlock
- iPhone-like delay after entering a wrong PIN
- EXIT button is blocked until the correct PIN is entered
- Logging to `/lock-for-bruce/logs.txt` (LittleFS)

### Under Development
- RFID tag unlock

---

## Installation
1. Upload `lock-for-bruce.js` to your Bruce device  
   - via **Bruce WebUI**, or  
   - via **Micro-SD card**
2. Open **Config → Startup App** in the Bruce firmware
3. Select **JS Interpreter**
4. Select **lock-for-bruce**
5. Reboot the device

On first startup, you will be prompted to **set a new PIN**.  
Afterwards, you must enter the PIN once to unlock Bruce.

---

## Settings & Configuration

### Open Settings
- Restart the device
- Press **OK 5 times** while the PIN field is empty

---

### Change PIN
1. Open **Settings**
2. Select **Reset Code**
3. Enter your current PIN
4. Enter the new PIN **twice** to confirm

---

### Enable Numpad Shuffle
1. Open **Settings**
2. Select **Shuffle**
3. Enter your PIN  
→ Numpad shuffle is enabled

---

### Enable Wrong PIN Delay
1. Open **Settings**
2. Select **Delay**
3. Enter your PIN  
→ Delay after wrong PIN entry is enabled
