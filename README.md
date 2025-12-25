# The Wheel Spin

A spinning wheel app for Twitch streamers — run giveaways, pick games, and create interactive moments with your viewers!

![Windows](https://img.shields.io/badge/Windows-10%2B-blue?logo=windows)
[![Latest Release](https://img.shields.io/github/v/release/Thadestroy/WheelSpinPickerReleases?label=Download)](https://github.com/Thadestroy/WheelSpinPickerReleases/releases/latest)

---

## Download & Install

**[Download Latest Version](https://github.com/Thadestroy/WheelSpinPickerReleases/releases/latest)**

### Installation Steps
1. Download the installer (`TheWheelSpinSetup_X.X.X.exe`)
2. Run the installer — **Windows may show a security warning:**
   - Click **"More info"**
   - Then click **"Run anyway"**
   - *(This appears because the app isn't signed with an expensive certificate yet)*
3. Follow the wizard — no admin required!

### Requirements
- Windows 10 or later
- Twitch account (optional, for chat integration)

---

## Features

### Beautiful Wheel
- Colorful animated wheel with smooth spin animations
- Displays viewer Twitch name colors on wheel slices
- Transparent background for easy OBS window capture overlay

### Twitch Chat Integration
- Viewers join the wheel via chat commands
- Mods and broadcaster control spins from chat
- Perfect for hands-free streaming

### Channel Point Redemptions
- Link wheel presets to your channel point rewards
- Automatically add users or trigger spins when redeemed
- Queue system manages multiple redemptions

### Presets & Sessions
- Save multiple wheel configurations
- Quick-launch your favorite wheels
- Crash recovery — never lose your entries if the app closes

### Stream Deck Ready
- Create custom commands for any preset
- One button press loads and optionally spins the wheel

---

## Chat Commands

### Viewer Commands
| Command | Description |
|---------|-------------|
| `!join` | Join the current wheel (when joining is enabled) |

### Mod & Broadcaster Commands
| Command | Description |
|---------|-------------|
| `!startwheelspin` | Start a new session with an empty wheel, enables `!join` |
| `!endwheelspin` | Stop accepting new entries |
| `!spinwheel` | Spin the wheel |
| `!resetwheelspin` | Clear the wheel and end the session |
| `!customcommand` | Any custom command you've set for a preset (e.g., `!gamepicker`) |

---

## OBS Setup

1. Add **Window Capture** source in OBS
2. Select "The Wheel Spin" window
3. Crop to show just the wheel area (it has a transparent background!)
4. Control everything via chat — no need to click on the app during stream

---

## Use Cases

| Scenario | How To |
|----------|--------|
| **Viewer Giveaway** | `!startwheelspin` → viewers `!join` → `!spinwheel` |
| **Game Selection** | Create a preset with game names → Quick Launch → Spin |
| **Channel Points** | Link a preset to a reward → viewers redeem to join or spin |
| **Stream Deck** | Set custom command on preset → bind to Stream Deck button |

---

## Updates

The app automatically checks for updates on launch and will notify you when a new version is available.

---

## Support & Feedback

Found a bug or have a feature request? [Open an issue](https://github.com/Thadestroy/WheelSpinPickerReleases/issues) or reach out on Twitch!

---

Made with love for the streaming community
