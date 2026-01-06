<div align="center">

  # 🎬 AylaStream
  ### A Synchronized Watch Party Experience

  ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
  ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
  ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
  ![Vite](https://img.shields.io/badge/Vite-B73C92?style=for-the-badge&logo=vite&logoColor=white)
  ![Hono](https://img.shields.io/badge/Hono-E36002?style=for-the-badge&logo=hono&logoColor=white)
  ![Bun](https://img.shields.io/badge/Bun-000000?style=for-the-badge&logo=bun&logoColor=white)

  <br />

  <img src="https://raw.githubusercontent.com/bitzin-dev/AylaStream/refs/heads/main/banner.png" alt="AylaStream Cover" width="100%" style="border-radius: 10px; box-shadow: 0px 0px 20px rgba(0,0,0,0.5);" />

</div>

<br />

## 💡 Why AylaStream?

Watching movies with friends online often comes with hurdles: quality drops on screen-share, sync issues, or intrusive ads on third-party services.

**AylaStream was built to simplify this:**
It's a focused video player that allows users to create synchronized rooms using **direct video URLs (MP4/HLS)**. The goal is to provide a stable, ad-free environment with an interface that feels familiar and easy to use.

[![Video Demonstration](https://img.shields.io/badge/VIDEO-DEMONSTRATION-000000?style=for-the-badge&logo=rocket&logoColor=white)](https://drive.google.com/file/d/1NE4yNDkwQc-PeIiO2cBRPkBAFTZKUahk/view)

---

## 📺 Features

### 1. The Player Experience
An interface inspired by modern streaming platforms, optimized for shared viewing.

<div align="center">
  <video src="https://github.com/bitzin-dev/AylaStream/raw/refs/heads/main/example.mp4" controls="controls" style="border-radius: 10px; box-shadow: 0px 0px 20px rgba(0,0,0,0.5); width:100%">
  <p><em>Demo: Seamless scrubbing, episode selection, and audio track switching.</em></p>
</div>

* **Clean UI:** Controls that stay out of the way during playback.
* **Playback Control:** Support for multiple audio tracks, subtitles (VTT), and adjustable playback speed.
* **Series Workflow:** Integrated episode selector and "Next Episode" prompts.
* **Visual Feedback:** Custom progress bar with buffering visualization.

### 2. Synchronization & Social
Keeps everyone on the same frame without cluttering the screen.

* **Real-Time Chat:** A simple overlay for communication.
* **Reactions:** Quick emoji interactions for shared moments.
* **Host-Based Sync:** The room follows the host's actions (play, pause, seek) to ensure everyone is in sync.
* **Presence:** Simple indicator of who is currently in the room.

---

## 🛠️ Technical Overview

The project focuses on a modern stack to ensure a fast and responsive interface.

* **Frontend:** React + Tailwind CSS for a modular and lightweight UI.
* **Backend (In progress):** Powered by **Bun** and **Hono**, focusing on minimal overhead and type-safety.
* **State Management:** Handles the synchronization between the video event loop and the UI state to ensure smooth updates across different browsers.
* **Optimistic Updates:** Chat and interactions are rendered instantly to provide a more native feel.

## 🔜 Upcoming Updates

The project is evolving from a frontend-heavy logic to a more robust backend integration:

* **WebSocket Integration:** Moving towards low-latency synchronization using Bun's native WebSockets.
* **Persistent Rooms:** Implementation of a Hono-based API for better room management.
* **Authentication:** Simple, secure access for persistent user settings.

---

## 📩 Contact

AylaStream is currently a work in progress.

If you have questions or just want to chat about the project, feel free to reach out:
**[bitzindev@proton.me](mailto:bitzindev@proton.me)**

<br />

<div align="center">
  
  <p>Built by Henrique</p>
  <p><em>A better way to watch together.</em></p>

</div>
