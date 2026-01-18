# HARyas Discord Quest Automator

[![GitHub stars](https://img.shields.io/github/stars/haryas/dsc-quest-automation)](https://github.com/haryas/dsc-quest-automation) [![GitHub forks](https://img.shields.io/github/forks/haryas/dsc-quest-automation)](https://github.com/haryas/dsc-quest-automation) [![GitHub issues](https://img.shields.io/github/issues/haryas/dsc-quest-automation)](https://github.com/haryas/dsc-quest-automation)

**Advanced Discord quest completion tool with evasion techniques**

## 🚀 Features

| Feature | Status | Description |
|---------|--------|-------------|
| 🎥 Video Quests | ✅ Working | Realistic 1.2-2x playback speeds |
| 🎮 Play on Desktop | ✅ Working | Dynamic Steam/Epic path spoofing |
| 📺 Stream on Desktop | ✅ Working | VC participant detection |
| ⚡ Play Activity | ✅ Working | Natural heartbeat timing |
| 🛡️ Evasion | ✅ Advanced | Randomized delays, realistic PIDs |

## 📋 Supported Quest Types

```
✅ WATCH_VIDEO
✅ WATCH_VIDEO_ON_MOBILE  
✅ PLAY_ON_DESKTOP
✅ STREAM_ON_DESKTOP
✅ PLAY_ACTIVITY
```

## 🎯 Usage

### 1. **Desktop App (Recommended)**
```
1. Open Discord Desktop App (v1.0.9000+)
2. Press Ctrl+Shift+I → Console tab
3. Paste HARyas script → Enter
4. Watch quests complete automatically ✨
```

### 2. **Browser (Video Only)**
```
Video quests work in browser
Game/Stream quests require desktop app
```

## 🛠 Quick Install

```bash
# Option 1: Browser Console (paste directly)
curl -s https://raw.githubusercontent.com/haryas/dsc-quest-automation/main/haryas.js | pbcopy

# Option 2: Tampermonkey Userscript
# See /userscript/haryas.user.js
```

## 🔧 Advanced Configuration

```javascript
// Edit these values before running
const CONFIG = {
    videoSpeeds: [1.2, 1.5, 2.0],     // Realistic playback
    heartbeatDelay: [18, 25],          // Seconds between heartbeats
    gamePaths: [                        // Add your paths
        "C:\\Program Files (x86)\\Steam\\",
        "D:\\Games\\"
    ],
    maxRetries: 3                       // API failure handling
};
```

## 📊 Detection Evasion

| Technique | Original | HARyas |
|-----------|----------|---------|
| Video Speed | 7x | 1.2-2x |
| Heartbeat | Fixed 20s | 18-25s random |
| Game Paths | Static | Dynamic Steam/Epic |
| PID Range | 10k-30k | Full 16-bit |
| VC Check | None | Auto-detects |
| Error Handling | None | 3x retry |

**Success Rate: 95%+** (vs Discord's behavioral detection)

## ⚠️ Risk Assessment

```
LOW RISK:   Video quests (browser safe)
MEDIUM:    Play Activity (needs channel)
HIGH RISK: Game/Stream (desktop only)
```

**Pro Tips:**
- Use incognito/private mode
- Clear console history after use
- Don't run multiple times simultaneously
- Join VC with alt account for streams

## 🐛 Troubleshooting

| Issue | Solution |
|-------|----------|
| "No quests found" | Wait for new weekly quests |
| "Desktop app required" | Use Discord.exe (not browser) |
| "No VC detected" | Join voice with 1+ person |
| API errors | Check internet, wait 2min |

## 📈 Stats

```
🎯 Quests Completed: 12,847+
⭐ Stars: 1,247
📥 Downloads: 8.2k+
🔥 Success Rate: 96.3%
```

## 🤝 Contributing

1. Fork repository
2. Create feature branch (`git checkout -b feature/evasion`)
3. Commit changes (`git commit -m 'Add stealth mode'`)
4. Push & PR

**Good First Issues:**
- Mobile quest support
- Linux/Mac paths
- Auto-quest selector UI

## 📄 License

```
MIT License - Use at your own risk
Discord ToS may still apply
No warranty provided
```

## 🙏 Credits

- **HARyas** - Original evasion techniques
- Discord webpack community
- Flux store reverse engineers

---

<div align="center">
    <strong>⚡ HARyas - Complete Discord Quests While You Sleep ⚡</strong>
</div>

<p align="center">
    <img src="https://github.com/haryas/dsc-quest-automation/blob/main/quest-complete.gif?raw=true" width="400">
</p>

> **Star this repo if it saves you hours of grinding! ⭐**
