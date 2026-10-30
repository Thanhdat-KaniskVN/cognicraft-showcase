<div align="center">
  <h1>🧠 CogniCraft OS</h1>
  <p><b>A Bio-Inspired Cognitive Operating System (Human-Centric AI)</b></p>
  <p>
    <img src="https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python" alt="Python">
    <img src="https://img.shields.io/badge/LLM-Groq%20%7C%20DeepSeek-orange?style=flat-square" alt="LLM">
    <img src="https://img.shields.io/badge/Status-Enterprise%20Grade-success?style=flat-square" alt="Status">
  </p>
  <p><i>"An AI that doesn't just answer questions, but understands your biology."</i></p>
</div>

---

## 📖 Overview

**CogniCraft OS** is a next-generation Cognitive Operating System designed to simulate human physiology and psychology accurately. Unlike traditional Chatbots, CogniCraft utilizes a proprietary **32-Layer Architecture** to "sense" the user's state (Stress, Brainwaves, Sleep Debt) and deliver tailored behavioral and educational interventions.

> 🔒 **Security Notice:** This is a **Showcase Repository**. The proprietary Core Engine is kept Private to protect Intellectual Property (IP). This repository demonstrates system capabilities, architecture, and performance benchmarks.

---

## 🚀 Core Capabilities

### 🧬 Dynamic Biology Engine
*   **Dual-layer Stress Simulation:** Real-time calculation of Adrenaline (SAM axis) and Cortisol (HPA axis).
*   **Sleep Architecture:** Tracks Sleep Debt and REM Debt based on Matthew Walker's sleep model.
*   **Neurological States:** Simulates Brainwave transitions (Alpha/Beta/Gamma) and Microglial inflammation.

### 🛡️ Behavioral Intervention
*   **System Guardian:** Automatically enforces device shutdown when physiological metrics indicate severe exhaustion.
*   **Emergency Override:** Bypasses guardian locks and injects simulated Adrenaline during critical situations.
*   **Zen Meditation:** Instant intervention to lower heart rate and shift Brainwaves to a relaxed Alpha state.

### 📅 Smart Scheduler
*   Generates personalized schedules based on **Circadian Rhythms** (Morning: Logic, Afternoon: Practice, Evening: Creativity).

---

## 🏗️ System Architecture

```mermaid
graph TD
    %% Styling
    classDef user fill:#f9f9f9,stroke:#333,stroke-width:2px;
    classDef frontend fill:#FF4B4B,color:white,stroke:#333,stroke-width:2px;
    classDef core fill:#8A2BE2,color:white,stroke:#333,stroke-width:2px;
    classDef layers fill:#2E86C1,color:white,stroke:#333,stroke-width:2px;
    classDef llm fill:#28B463,color:white,stroke:#333,stroke-width:2px;

    User([👤 User]):::user -->|Chat / Actions| UI[💻 Streamlit Frontend]:::frontend
    UI --> CPM[⚙️ CPM-16 Microprocessor]:::core

    subgraph Core Architecture
        CPM --> Bio[🧬 Core Biology Layer]:::layers
        CPM --> Cog[🧠 Core Cognition Layer]:::layers
        CPM --> Int[🛡️ Intervention Layer]:::layers
    end

    Bio --> LLM[🏦 LLM Routing & API Bank]:::llm
    Cog --> LLM
    Int --> LLM

    LLM -->|Response| UI
