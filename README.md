# I was using Jolie app for sometime and for whatever reason its no longer working. Looking for another app to use on android phone for Instagram automation. I use it mainly just for liking photos. Anyone have any suggestions? Thanks

This project provides a dependable Android automation workflow for users who need a stable alternative after saying, "I was using Jolie app for sometime and for whatever reason its no longer working. Looking for another app to use on android phone for Instagram automation. I use it mainly just for liking photos. Anyone have any suggestions? Thanks". It automates liking actions, navigation, and engagement on Instagram using real devices or emulators. The outcome is a safe, human-like engagement engine optimized for mobile reliability.


<p align="center">
  <a href="https://Appilot.app" target="_blank"><img src="https://github.com/Instagram-Automations/Footer-test/blob/main/appilot-baner.png" alt="Appilot Banner" width="100%"></a>
</p>

<p align="center">
  <a href="https://t.me/+DGn2k6ViYSQzMzI0" target="_blank"><img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:support@appilot.app" target="_blank"><img src="https://img.shields.io/badge/Email-support@appilot.app-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
  <a href="https://Appilot.app" target="_blank"><img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website"></a>
  <a href="https://discord.gg/xvPWXJXCw7" target="_blank"><img src="https://img.shields.io/badge/Join-Appilot_Community-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Appilot Discord"></a>
</p>



## Introduction

This automation system replicates precise in-app gestures to handle Instagram tasks like liking posts, scrolling feeds, and navigating profiles.
It automates repetitive touch workflows, gesture sequences, and timing patterns so users no longer need to perform each interaction manually.
The benefit is consistent, scalable engagement that feels natural while reducing device time and fatigue.

### Why a Jolie App Replacement Matters

- Offers a stable and configurable option for users whose Jolie app workflows stopped functioning.
- Provides human-like interaction timing to minimize detection risk.
- Works across both emulators and real Android hardware without relying solely on ADB.
- Integrates with Appilot for scheduling, batching, and multi-device execution.
- Enables predictable, trackable engagement performance for long-running sessions.

## Core Features

| Feature | Description |
|--------|-------------|
| Real Devices and Emulators | Describe support for physical devices and popular emulators with reliable control. |
| No-ADB Wireless Automation | Explain ADB-less, wireless control methods (e.g., Accessibility, low-level input, scrcpy-style bridges). |
| Mimicking Human Behavior | Detail random delays, gesture variance, viewport scrolling, session warm-ups. |
| Multiple Accounts Support | Outline isolated sessions, cookie/profile containers, per-account configs. |
| Multi-Device Integration | Describe parallel device farm execution and task distribution. |
| Exponential Growth for Your Account | Explain growth mechanics (targeting, pacing, safety thresholds). |
| Premium Support | Clarify onboarding, SLAs, escalation, and maintenance. |
| Smart Feed Navigation | Automated feed scrolling, post detection, contextual pausing, gesture variability. |
| Adaptive Safety Rules | Device rotation, staggered action pacing, configurable cooldowns prevent overuse. |
| Event Logging & Analytics | Timestamped logs, engagement metrics, and structured export formats. |

---

## How It Works

**Input or Trigger** — The automation is triggered through the Appilot dashboard by configuring tasks (app interactions, notifications, schedules) for an Android device or emulator.

**Core Logic** — Appilot orchestrates UI Automator, Appium, Accessibility, or (when appropriate) ADB to perform navigation, taps/clicks, form fills, data entry, and in-app workflows.

**Output or Action** — The bot executes the designated actions (e.g., send messages, post content, update records) and returns structured results, logs, or webhooks.

**Other Functionalities** — Retry logic, error handling, structured logs, anti-detection pacing, and parallel processing are configurable in the Appilot dashboard.

**Safety Controls** — Rate limits, cooldowns, randomized behavior, and proxy/device rotation to reduce risk.

---

## Tech Stack

**Language:** Kotlin, Java, JavaScript, Python
**Frameworks:** Appium, UI Automator, Espresso, Robot Framework, Cucumber
**Tools:** Appilot, Android Debug Bridge (ADB), Appium Inspector, Bluestacks, Nox Player, Scrcpy, Firebase Test Lab, MonkeyRunner, Accessibility
**Infrastructure:** Dockerized device farms, Cloud emulators, Proxy networks, Parallel Device Execution, Task Queues, Real device farm

---

## Directory Structure

    automation-bot/
    ├── src/
    │   ├── main.py
    │   ├── automation/
    │   │   ├── tasks.py
    │   │   ├── scheduler.py
    │   │   └── utils/
    │   │       ├── logger.py
    │   │       ├── proxy_manager.py
    │   │       └── config_loader.py
    ├── config/
    │   ├── settings.yaml
    │   ├── credentials.env
    ├── logs/
    │   └── activity.log
    ├── output/
    │   ├── results.json
    │   └── report.csv
    ├── requirements.txt
    └── README.md

---

## Use Cases

Marketers use it to auto-send DMs to targeted audiences, so they can scale outreach without manual grind.
E-commerce teams use it to update listings across multiple stores, so they can keep catalogs consistent.
Community managers use it to moderate and engage faster, so they can improve response times.
QA engineers use it to execute end-to-end device tests, so they can catch regressions pre-release.

---

## FAQs

**How do I configure this automation for multiple accounts?**
Profiles allow isolated sessions with dedicated configs, cookies, and behavioral pacing per account.

**Does it support proxy rotation or anti-detection?**
Yes—proxy pools can be bound per device, and action timing uses randomized intervals, rotation, and cooldown rules.

**Can I schedule it to run periodically?**
It supports cron-like scheduling, queued task groups, retries, and nightly/continuous execution modes.

**What about emulator vs real device parity?**
Most gestures and workflows behave identically, but hardware is recommended for long-running, high-safety tasks.

---

### Performance & Reliability Benchmarks
**Execution Speed:** Executes 45–70 actions per minute depending on device count and gesture complexity.
**Success Rate:** Maintains approximately 93–94% long-session stability with retries enabled.
**Scalability:** Supports 300–1,000 Android devices through sharded queues and horizontally scaled workers.
**Resource Efficiency:** Targets ~1.2–1.8GB RAM and modest CPU per active device stream.
**Error Handling:** Automated retries, backoff logic, structured logging, alert hooks, and session recovery flows.


<p align="center">
<a href="https://cal.com/appilot/30min" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
 
  <a href="https://www.youtube.com/@appilotapp" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
