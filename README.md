# Streamer.bot Multi-Platform Chat Overlay Studio

A fully customizable, single-file HTML studio and OBS overlay generator that connects directly to Streamer.bot via WebSocket to capture live chat from **Twitch**, **YouTube**, and **Kick**.

---

## 🚀 Features

- **Multi-Platform Support**: Real-time event handling for **Twitch** (`Twitch.ChatMessage`), **YouTube** (`YouTube.Message`), and **Kick** (`Kick.ChatMessage`).
- **One-Click OBS Export**: Instantly download a standalone `obs-chat-overlay.html` file configured with your exact settings for use as an OBS Browser Source.
- **Dynamic Styling & Presets**: Includes multiple built-in layout styles (Bubbles, Plain Text, Glassmorphism, Cyberpunk, Retro Terminal, Luxury Gold).
- **Smooth Animations**: Configurable entrance animations and stack sliding with an optional **🎲 Random Effect on Each Message** mode.
- **Typography**: Supports popular Google Web Fonts and standard Windows system fonts.
- **Audio Alerts**: Built-in Web Audio API sound synthesizers (Beep, Pop, Chime) with options for random sounds or local file playback (`./sound.mp3`).
- **Background & Border Control**: Transparent OBS mode, solid colors, gradient fade-outs, and local `image.png` border/background support.
- **Moderation & Security**: 
  - Automatic removal of messages when a user is banned, timed out, or messages are deleted by moderators.
  - Built-in filters for swear words, custom blacklists, and web links/URLs.
  - User badges (Mod, VIP, Subscriber) and platform profile pictures.

---

## 🛠️ How to Use

1. **Save the Studio File**: Copy the complete HTML code provided above and save it locally on your computer as `index.html`.
2. **Open in Browser**: Double-click the file to open it in any modern web browser (Chrome, Firefox, Edge).
3. **Connect to Streamer.bot**: Ensure Streamer.bot is running locally and its WebSocket server is active (default: `ws://127.0.0.1:8080/`), then click **Connect**.
4. **Test the Overlay**: Use the built-in simulation bar at the bottom of the studio to test messages from Twitch, YouTube, and Kick.
5. **Export for OBS**: Click **💾 Export OBS Overlay (.html)**, save the exported file into your local project folder (alongside any custom `image.png` or `sound.mp3` files if used), and add it as a **Browser Source** in OBS Studio.
