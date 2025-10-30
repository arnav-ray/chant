# 🕉️ Spiritual Chanting Counter App

A beautiful, distraction-free app to help track your mantra chanting practice with elegant visual feedback and optional background music.

![Version](https://img.shields.io/badge/version-1.0.0-orange)
![Platform](https://img.shields.io/badge/platform-Web%20%7C%20Android-blue)
![License](https://img.shields.io/badge/license-MIT-green)

---

## 📖 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Demo](#demo)
- [Getting Started](#getting-started)
- [How to Use](#how-to-use)
- [Technical Stack](#technical-stack)
- [Browser Support](#browser-support)
- [Installation](#installation)
- [Development](#development)
- [Building for Production](#building-for-production)
- [Android Deployment](#android-deployment)
- [Contributing](#contributing)
- [Roadmap](#roadmap)
- [FAQ](#faq)
- [License](#license)
- [Contact](#contact)

---

## 🌟 Overview

The Spiritual Chanting Counter App is designed for spiritual practitioners who want to track their mantra repetitions with beautiful, distraction-free visual feedback. Whether you're chanting Om, Hare Krishna, or your own custom mantra, this app provides an immersive and focused experience.

### Why This App?

- **Distraction-Free:** No ads, no clutter, just pure spiritual practice
- **Beautiful Visualization:** Watch your chosen mantra fill with deepening color as you progress
- **Flexible:** Supports any mantra and any count (9, 108, 1001, 10,000+)
- **Immersive:** Optional background music or upload your own spiritual music
- **Offline First:** Works completely offline, no internet required
- **No Registration:** Start chanting immediately, no account needed

---

## ✨ Features

### Current Features (v1.0)

#### 🎯 **Chant Selection**
- Pre-set popular mantras:
  - Om (ॐ)
  - Radhe Radhe
  - Hare Krishna Maha Mantra
  - Om Namah Shivaya
- Custom chant input for any mantra

#### 🔢 **Flexible Counting**
- Quick select: 9, 108, 1001, 10001
- Custom count: Enter any number (1-100,000)
- Real-time completed/remaining counter

#### 🎨 **Visual Progress**
- Unique gradient-fill visualization
- Chant word fills from light to deep orange
- Opacity increases with progress (30% → 100%)
- Multi-line support for long mantras
- Auto-scaling font for perfect fit

#### 🎵 **Background Music**
- Three options:
  1. Auto-selected ambient sound (peaceful drone)
  2. Upload your own music (MP3, WAV)
  3. Silent mode
- Pause/play controls
- Continuous loop playback

#### 🎉 **Completion Celebration**
- Congratulations screen
- Session statistics
- Options to continue or start new session

#### 🎨 **Beautiful Design**
- Warm spiritual color palette (orange, cream)
- Smooth animations
- Responsive design (works on all screen sizes)
- Clean, modern interface

---

## 🎬 Demo

### Screenshots

**Selection Screen:**
```
Choose your mantra, set your count, select music preference
```

**Chanting Screen:**
```
Large mantra display with gradient fill showing progress
```

**Completion Screen:**
```
Celebration with option to continue or start new session
```

### Live Demo

Try it now: [Chanting App Demo](#) *(link to be added after deployment)*

---

## 🚀 Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required for web version
- For Android: Android 6.0+ device

### Quick Start (Web)

1. Open the `chanting-app.html` file in your web browser
2. Select your chant (or enter custom)
3. Choose your count
4. Optionally select music
5. Click "Begin Chanting"
6. Start tapping the CHANT button!

That's it! No setup, no configuration, just start chanting.

---

## 📱 How to Use

### Step-by-Step Guide

#### 1. **Select Your Chant**

Click one of the preset chant buttons:
- **Om** - The primordial sound
- **Radhe Radhe** - Devotion to Radha
- **Hare Krishna** - The Maha Mantra (full 16-word version)
- **Om Namah Shivaya** - Salutation to Shiva

Or enter your own custom chant in the text field below.

**Tip:** The selected button will turn deep ocean blue.

---

#### 2. **Set Your Count**

Click one of the preset count buttons:
- **9** - Quick practice
- **108** - Traditional mala count
- **1001** - Extended practice
- **10001** - Advanced sadhana

Or enter your own custom count (up to 100,000).

**Tip:** 108 is the traditional count in Hinduism, representing spiritual completion.

---

#### 3. **Choose Background Music (Optional)**

Select one of three options:
- **Auto-selected ambient** - Simple drone sound (default)
- **Upload your own music** - Browse and select your MP3/WAV file
- **No music** - Silent chanting

**Tip:** For the most authentic experience, upload traditional Indian classical music or bhajans.

---

#### 4. **Begin Chanting**

Click the "Begin Chanting" button. You'll see:
- Your chosen mantra displayed large in the center
- Completed and Remaining counters
- Large orange CHANT button
- Music controls and Back button

---

#### 5. **Count Your Chants**

Tap the CHANT button once for each repetition of your mantra.

**What happens:**
- Counter increments
- Mantra visualization fills with deeper orange gradient
- Brief sound plays (if music enabled)
- Button provides tactile feedback

**Tip:** Find a comfortable rhythm. Some prefer one tap per complete mantra, others tap on each breath.

---

#### 6. **Complete Your Session**

When you reach your target count:
- Congratulations screen appears automatically
- See your session summary
- Choose to continue or start a new session

**Options:**
- **Continue Chanting** - Adds the same count to your total
- **New Session** - Returns to selection screen

---

#### 7. **Going Back**

Use the "← Back" button if you need to:
- Change your chant
- Adjust your count
- Select different music

**Note:** If you have progress, you'll be asked to confirm before losing it.

---

## 🛠 Technical Stack

### Technologies Used

**Frontend:**
- HTML5
- CSS3 (with gradients, animations)
- Vanilla JavaScript (ES6+)

**APIs:**
- HTML5 Canvas API (for gradient visualization)
- Web Audio API (for ambient sound generation)
- HTML5 Audio Element (for uploaded music)
- File API (for music upload)

**No Dependencies:**
- Zero external libraries
- Zero frameworks
- Pure, clean code
- ~500 lines total

---

## 🌐 Browser Support

### Fully Supported

✅ **Chrome/Chromium** 90+  
✅ **Firefox** 88+  
✅ **Safari** 14+  
✅ **Edge** 90+  

### Required Features

- HTML5 Canvas 2D Context
- CSS3 (gradients, transforms, animations)
- ES6 JavaScript (arrow functions, template literals, etc.)
- Web Audio API (for ambient sound)
- HTML5 Audio (for uploaded music)
- File API (for music upload)

### Fallback Behavior

If a feature isn't supported:
- **No Canvas:** Falls back to text-based progress
- **No Web Audio:** Skips ambient sound
- **No File API:** Hides upload option

---


## 🤝 Contributing

We welcome contributions! Here's how you can help:

### Ways to Contribute

1. **Report Bugs**
   - Use GitHub Issues
   - Provide detailed reproduction steps
   - Include browser/device information

2. **Suggest Features**
   - Check existing feature requests
   - Explain use case and benefits
   - Consider scope and complexity

3. **Submit Pull Requests**
   - Fork the repository
   - Create feature branch
   - Write clear commit messages
   - Test thoroughly
   - Submit PR with description

4. **Improve Documentation**
   - Fix typos
   - Add examples
   - Clarify instructions
   - Translate to other languages

### Development Guidelines

**Code Style:**
- Use meaningful variable names
- Add comments for complex logic
- Follow existing formatting
- Keep functions small and focused

**Testing:**
- Test on multiple browsers
- Test on different screen sizes
- Test with different chants (short, long)
- Test edge cases (very large counts, special characters)

**Commit Messages:**
```
feat: Add new chant preset
fix: Canvas rendering on small screens
docs: Update installation instructions
style: Improve button animations
```

---


---

## ❓ FAQ

### General Questions

**Q: Is the app really free?**  
A: Yes, 100% free. No ads, no in-app purchases, no hidden costs.

**Q: Do I need an internet connection?**  
A: No. The app works completely offline after the initial load.

**Q: Do I need to create an account?**  
A: No. No registration, no login, no personal information required.

**Q: What data does the app collect?**  
A: Currently, none. All data stays on your device locally.

---

### Usage Questions

**Q: What is the significance of 108?**  
A: In Hinduism, 108 is considered sacred. Malas (prayer beads) traditionally have 108 beads, representing the 108 names of God, 108 Upanishads, or other spiritual concepts.

**Q: Can I use this for non-Hindu mantras?**  
A: Absolutely! Use the custom chant input for any mantra, affirmation, or prayer.

**Q: My text is getting cut off. What should I do?**  
A: The app automatically scales and wraps text. Very long chants (50+ characters) may use smaller fonts. Consider using abbreviations if needed.

**Q: Can I use my own background music?**  
A: Yes! Use the "Upload your own music" option and select any MP3 or WAV file from your device.

**Q: The music upload isn't working. Why?**  
A: Ensure your file is under 50MB and is in MP3 or WAV format. Some browsers may block file access for security reasons.

---

### Technical Questions

**Q: Why isn't the app working in my browser?**  
A: The app requires a modern browser (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+). Update your browser to the latest version.

**Q: Can I use this on my phone?**  
A: Yes! The web version works on mobile browsers. An Android app version is coming soon.

**Q: The app is slow. How can I improve performance?**  
A: Close other tabs, restart your browser, or try a different browser. The app is lightweight (<1MB) and should run smoothly on most devices.

**Q: Can I modify the code?**  
A: Yes! The code is open and you're free to modify it for personal use. See the [License](#license) section.

**Q: How do I report a bug?**  
A: Open an issue on GitHub with detailed steps to reproduce, browser/device info, and screenshots if possible.

---

### Privacy & Security

**Q: Is my data safe?**  
A: Your data never leaves your device. Everything is stored locally in your browser's memory.

**Q: Can you see my chanting statistics?**  
A: No. We cannot and do not collect any data from the app.

**Q: Does the app require any permissions?**  
A: The web version requires no permissions. The Android version will only require storage permission (for uploaded music).

---

## 📄 License

MIT License

Copyright (c) 2025 Spiritual Chanting App

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---


## 🌟 Show Your Support

If this app helps your spiritual practice, please:
- ⭐ Star this repository
- 🐛 Report any bugs you find
- 💡 Suggest new features
- 📢 Share with fellow practitioners
- 📝 Write a review on the Play Store (when released)

---

**Made with 🧡 for spiritual seekers everywhere**

*Last Updated: October 30, 2025*  
*Version: 1.0.0*  
*Status: Active Development*
