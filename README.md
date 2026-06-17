# 👀 Blink

A cute macOS menu bar app that reminds you to blink and rest your eyes every 1.5 hours.

Built because my ophthalmologist told me to blink more.

---

## ✨ Features

- 🕐 Reminds you to take a **20-second blinking break**
- 🐈 Cute animated cat character watches you blink
- 🔥 Tracks your daily streak with fire icons (resets at midnight)
- ⏰ 10-second pre-warning countdown in the menu bar before each break
- 🖱️ Click anywhere during a break to dismiss + snooze 15 minutes (no streak earned)
- ✅ Only completed 20-second breaks count toward your streak
- 🪶 Lives quietly in your menu bar — no Dock icon

---

## 📦 Installation

### Option A — Download the pre-built app (easiest)

1. Go to the [**Releases**](https://github.com/anaghaachakrapani/Blink/releases) page
2. Download `Blink.app.zip` from the latest release
3. Unzip and drag `Blink.app` into your **Applications** folder
4. **First launch:** because Blink isn't notarised by Apple (cost reasons), macOS will show a warning. To fix:
   - **Right-click** `Blink.app` → **Open**
   - Click **Open** in the dialog that appears
   - You only have to do this once
5. Look at your menu bar — you should see two cute eyes 👀


---

## 🛠️ How it works

| State | Duration | Menu bar shows |
|---|---|---|
| Idle | 1h 29m 50s | Cute eyes, static |
| Pre-warning | 10s | Eyes + countdown `10`, `9`, `8`... |
| Break | 20s | Eyes **blinking** + yellow popup with animated cat |
| Snooze | 15min | Eyes static (returns to idle after) |

**Streak rules:**
- Earn 1 fire 🔥 for every completed 20s break
- Click outside the popup during a break = no streak, snooze 15min
- Streak resets at 23:59 every day

---

## 🎨 Credits

- Cat character design inspired by Jiji from *Kiki's Delivery Service*
- Calcifer streak icon from *Howl's Moving Castle*
- Font: [Berkshire Swash](https://fonts.google.com/specimen/Berkshire+Swash) (Google Fonts, SIL Open Font License)

---

## 🤝 Contributing

PRs welcome! If you spot a bug or have an idea, open an issue.

---

## 📄 License

[MIT](LICENSE) — do whatever you want with it.
