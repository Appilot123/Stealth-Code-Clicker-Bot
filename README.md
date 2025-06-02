<h1 align="center">Stealth Code Clicker Bot</h1>

## Project Overview:

This lightweight automation bot is built to mimic human behavior while performing a simple yet critical task: clicking a button on a website at specific intervals to generate a code, then logging that code either locally or into a Google Sheet. It’s designed to operate undetected—ideal for use cases where automation cloaking is a must. The tool solves a niche need: trigger-time precision with stealth, making it perfect for time-based reward systems, booking windows, or daily claim actions.


## Core Features:
- **Undetectable Behavior:** Mimics human input via randomized delays, viewport simulation, and natural cursor movement to avoid bot detection.
- **Scheduled Action Execution:** Triggers button clicks at fixed or randomized intervals using background timers and error-handled task loops.
- **Flexible Data Logging:** Easily logs output to local files (JSON/CSV) or directly into a Google Sheet via API integration.

<div align="center">
  <img
    src="https://github.com/user-attachments/assets/d200549d-7613-446f-a43b-19a4117ca360"
    alt="select device"
    width="600px"
  />
</div>


<div align="center">
  <a href="https://appilot.app/">
    <img
      alt="Website"
      width="25px"
      src="https://github.com/user-attachments/assets/8e5f3af3-b098-4c1d-980d-df9aebc680d0"
    />
    <code>Appilot Website</code>
  </a>
  &nbsp;&nbsp;
  <a href="https://discord.gg/3CZ5muJdF2">
    <img
      alt="Join Our Server"
      width="30px"
      src="https://github.com/Zeeshanahmad4/RealEstateMate-WhatsApp-Group-Management-Bot/blob/main/discord-icon-svgrepo-com.svg"
    />
    <code>Join Our Server</code>
  </a>
  &nbsp;&nbsp;
  <a href="https://t.me/devpilot1">
    <img
      alt="Contact us"
      width="30px"
      src="https://edent.github.io/SuperTinyIcons/images/svg/telegram.svg"
    />
    <code>Contact Us</code>
  </a>
</div>

<div align="center">
<strong> Need a Custom Bot or Stealth Engagement Flow??</strong>

<div align="center">
  <a href="mailto:support@appilot.app">
  <img
    alt="Email"
    width="30px"
    src="https://github.com/user-attachments/assets/91c8d428-32b7-4be0-91fa-2e42c902b5b8"
  />
  <code>support@appilot.app</code>
</a>
  &nbsp;&nbsp;
  <a href="https://cal.com/app-pilot-m8i8oo/30min">
  <img
    alt="Book a 30-minute Call"
    width="30px"
    src="https://github.com/user-attachments/assets/cd3e5c7b-3e4e-4bb3-b242-bcc20ee78f13"
  />
  <code>Book a 30-minute Call</code>
</a>
<span>

<div align="left">

## Features List:
| Feature                     | Description                                                               |
| --------------------------- | ------------------------------------------------------------------------- |
| Proxy Integration           | Optionally supports rotating proxies to avoid IP-based flagging.          |
| Fingerprint Spoofing        | Uses randomized user-agents and screen sizes to spoof real browsers.      |
| Human-like Input Simulation | Incorporates random cursor paths, typing delays, and click timings.       |
| Time-Based Triggering       | Automatically clicks target button at defined or randomized intervals.    |
| Code Extraction             | Grabs generated code from the page DOM and stores it securely.            |
| Google Sheets Sync          | Pushes data to Google Sheets via Sheets API (OAuth-based).                |
| File Logging                | Logs all captured data into CSV/JSON with timestamps.                     |
| Headless & Headful Modes    | Run in visible browser or background mode depending on the stealth needs. |
| Session Recovery            | Recovers gracefully if the page reloads, disconnects, or fails.           |
| Easy Config Panel           | Adjust interval timing, target selectors, and output preferences easily.  |


## Key Stats:
- **Automation Accuracy:** 98%
- **Session Stability:** 24/7 runtime with auto-recovery
- **Concurrent Instances:** Supports 50+ tabs per machine (scalable with containers)
- **Human Detection Avoidance:** >99% success under anti-bot systems

## Built With:
- **Playwright + Stealth Plugins** (or Puppeteer-stealth)
- **Node.js** for core logic and timing
- **Google Sheets API** for optional logging
- **Multilogin / GoLogin** (optional for advanced fingerprinting)
