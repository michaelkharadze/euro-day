# Euroday

An Android app that uses on‑device machine learning to **detect and distinguish European coins** in real time. Built in **Android Studio (Kotlin)**, with a supporting **Python data pipeline** (pandas, matplotlib) used during development to aggregate >1M data points and visualize model behavior.

**Download:** `euroday.apk` (in this repository)

---

## Table of contents

* [Features](#features)
* [Tech stack](#tech-stack)
* [Getting started](#getting-started)

---

## Features

* **Real‑time coin recognition** — classify EU coins from the camera or gallery, with confidence scores.
* **Built for speed & scale** — data aggregation pipeline engineered to handle **1M+ data points** in near real time.
* **Faster analytics** — processing optimizations delivered \~**30%** reduction in pipeline runtime, enabling quick iteration on model quality.
* **Practical UX** — simple capture flow to reduce user error and avoid confusion between visually similar coins.

---

## Tech stack

* **Mobile app:** Kotlin, Android Studio.
* **ML/data tooling (development):** Python, pandas, matplotlib.
* **Model integration:** On‑device inference; model artifact bundled with the APK.
* **Target platform:** Android phones/tablets; modern Android versions recommended.

---

## Getting started

### 1) Get the APK

Download `euroday.apk` from this repository to your Android device (or transfer it via USB/AirDrop/Drive).

### 2) Allow installs from unknown sources

On your device, enable installing apps from your browser or file manager:

* **Settings → Security → Install unknown apps** (wording varies by device/OEM).

### 3) Install

Open the APK and follow the prompts to install **Euroday**.

### 4) Run & grant permissions

Launch the app and grant **Camera** permission when prompted.

**Tips for best results**

* Hold the coin flat, with good lighting and minimal glare.
* Fill a reasonable portion of the frame; avoid motion blur.
* Try multiple angles if the confidence is low.
