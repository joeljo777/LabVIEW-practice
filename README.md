# 🎛️ LabVIEW Practice & Projects

[![LabVIEW](https://img.shields.io/badge/Platform-NI%20LabVIEW-F0C000?style=for-the-badge&logo=nationalinstruments&logoColor=black)](https://www.ni.com/en-us/shop/labview.html)
[![Projects](https://img.shields.io/badge/VIs-40%20Programs-blue?style=for-the-badge)](#-catalog-of-vis)
[![Status](https://img.shields.io/badge/Status-Active%20Practice-success?style=for-the-badge)](#)

A comprehensive collection of National Instruments **LabVIEW** Virtual Instruments (`.vi`) developed for learning and experimenting with graphical programming (G code). This repository covers foundational logic, algorithmic problem solving, hardware emulation, signal generation, audio processing, File I/O, and interactive mini-games.

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Project Highlights](#-project-highlights)
- [Catalog of VIs](#-catalog-of-vis)
  - [1. Digital Logic & Circuit Simulation](#1-digital-logic--circuit-simulation)
  - [2. Control Structures & Core Programming](#2-control-structures--core-programming)
  - [3. Data Structures & Math Algorithms](#3-data-structures--math-algorithms)
  - [4. File Input / Output (I/O)](#4-file-input--output-io)
  - [5. Signals, Waveforms & Visualization](#5-signals-waveforms--visualization)
  - [6. Audio & Speech Processing](#6-audio--speech-processing)
  - [7. Interactive Games & GUI Applications](#7-interactive-games--gui-applications)
  - [8. Introductory Experiments](#8-introductory-experiments)
- [Requirements & Getting Started](#-requirements--getting-started)
- [Repository Structure](#-repository-structure)

---

## 🌟 Overview

LabVIEW (Laboratory Virtual Instrument Engineering Workbench) is a systems engineering software designed for test, measurement, and control. This repository tracks hands-on practice modules covering:

- **Graphical Dataflow**: Wires, data types, structures, and execution flow.
- **SubVIs & Modularity**: Creating reusable sub-routines (e.g., factorial calculator).
- **Signal Analysis**: Waveform synthesis, charting, and multi-channel signals.
- **Multimedia Integration**: Audio acquisition, real-time feedback, and speech synthesis.
- **Data Persistence**: CSV, plain text, and binary read/write pipelines.

---

## 🚀 Project Highlights

| Project | VI Name | Description |
|---|---|---|
| 🎹 **Virtual Piano** | `piano.vi` | Interactive keyboard instrument that synthesizes musical frequencies upon user interaction. |
| 🐱 **Talking Tom** | `talking tom.vi` | Voice recording, pitch/playback transformation, mimicking the classic talking mascot app. |
| 🎛️ **Signal Generator** | `Signal generator.vi` | Synthesizes standard waveforms (sine, square, triangular, sawtooth) with adjustable amplitude and frequency. |
| 🚦 **Traffic Controller** | `traffic light using flat sequence.vi` | Multi-phase traffic light sequencing implemented with Flat Sequence structures and timed delays. |
| 🎯 **Catch Me If You Can** | `catch me if u can.vi` | Interactive GUI game where controls dynamically move across the Front Panel to test user reaction. |
| 🗣️ **Text-to-Speech** | `text_to_speech.vi` | Speech synthesis utilizing OS text-to-speech engine APIs within LabVIEW. |

---

## 📂 Catalog of VIs

### 1. Digital Logic & Circuit Simulation
Implementation of digital electronics building blocks:
- `HALF_ADDER.vi` — Half adder circuit using XOR and AND boolean logic.
- `FULL_ADDER.vi` — Full adder circuit supporting Carry-In (`Cin`), Sum, and Carry-Out (`Cout`).
- `7 segment display.vi` — Seven-segment LED display logic / BCD-to-7-segment decoder.

### 2. Control Structures & Core Programming
Foundational LabVIEW structures and program flow control:
- `for loop.vi` — For Loop mechanics, iteration counts, and tunnel indexing.
- `while loop.vi` — While Loop execution with conditional stop indicators.
- `case selector.vi` — Case structures handling Boolean, numeric, or string conditions.
- `case --- calculator.vi` — Multi-function arithmetic calculator built using Case structures.
- `cal.vi` — Lightweight arithmetic calculator.
- `pass_and_fail.vi` — Grading and threshold evaluation using comparison logic.
- `traffic light using flat sequence.vi` — Timed multi-stage execution using Flat Sequence structures.
- `debugging.vi` — Demonstrates execution highlighting and probe tools.
- `breakpoints and other debugging techniques.vi` — Debugging workflows with breakpoints, pauses, and probe points.

### 3. Data Structures & Math Algorithms
Arrays, clusters, and algorithmic calculations:
- `Array_operation.vi` — Array creation, indexing, subset extraction, manipulation, and transformations.
- `clusters.vi` — Bundling, unbundling, and managing heterogeneous data clusters.
- `FACTORIAL SUB VI.vi` — Modular SubVI calculating factorials ($n!$).
- `permutation.vi` — Permutation ($nPr$) calculations combining modular logic.
- `pallindrome.vi` — Logic to test whether a given sequence, number, or string reads the same forwards and backwards.

### 4. File Input / Output (I/O)
File handling, serialization, and data logging:
- `FILE ONLY READ.vi` — Reading lines and contents from text files.
- `file read and write.vi` — Complete file writing and reading verification pipeline.
- `csv file.vi` — Standard CSV file handling and formatting.
- `csv write.vi` — Writing tabular data arrays into comma-separated values format.
- `csv read.vi` — Parsing comma-separated files into LabVIEW data structures.
- `write binary.vi` — High-efficiency binary file writing.
- `read binary.vi` — Binary data deserialization and reading.
- `sine to file (csv).vi` — Generates a sine waveform and serializes the points into a CSV log (`cSv.csv`).
- `read sine to file data.vi` — Reads and plots exported sine waveform data from disk.
- `cSv.csv` — Sample generated waveform dataset.

### 5. Signals, Waveforms & Visualization
Signal synthesis and real-time plotting:
- `Signal generator.vi` — Flexible function generator with variable frequency, amplitude, and waveform types.
- `waveform control.vi` — Manipulating waveform data attributes ($t_0$, $dt$, and $Y$ data array).
- `waveform_chart.vi` — Real-time waveform streaming and charting techniques (strip, scope, and sweep modes).

### 6. Audio & Speech Processing
Sound card interfacing and speech tools:
- `audio_input.vi` — Acquiring sound card / microphone samples and plotting incoming signals.
- `text_to_speech.vi` — Text-to-speech synthesis invoking system speech libraries.
- `talking tom.vi` — Voice recording, processing, and playback application.

### 7. Interactive Games & GUI Applications
Front panel interactivity and playful applications:
- `piano.vi` — Playable digital piano Front Panel with sound generation.
- `catch me if u can.vi` — Evasive button reaction game leveraging property nodes.

### 8. Introductory Experiments
- `Untitled 1.vi` through `Untitled 5.vi` — Introductory exploratory labs covering basic controls, arithmetic blocks, and wiring experiments.

---

## 🛠️ Requirements & Getting Started

### Prerequisites
- **National Instruments LabVIEW** (2018 or newer recommended, Base, Full, or Professional Development System).
- Windows OS (recommended for sound API and ActiveX/COM `.NET` speech dependencies).
- Audio input/output devices (Microphone & Speakers) for audio and piano VIs.

### How to Run
1. **Clone the repository**:
   ```bash
   git clone https://github.com/joeljo777/LabVIEW-practice.git
   cd LabVIEW-practice
   ```
2. **Open in LabVIEW**:
   - Launch NI LabVIEW.
   - Choose `File` > `Open` and browse to the desired `.vi` file.
3. **Execute**:
   - Switch between the **Front Panel** (`Ctrl + E`) for user controls and the **Block Diagram** (`Ctrl + E`) to inspect the G code.
   - Click the **Run** button (`Ctrl + R`) or **Continuous Run** to execute.

---

## 📂 Repository File Tree

```text
LabVIEW-practice/
│
├── 📁 Digital Logic & Circuits
│   ├── 7 segment display.vi
│   ├── FULL_ADDER.vi
│   └── HALF_ADDER.vi
│
├── 📁 Structures & Control Flow
│   ├── breakpoints and other debugging techniques.vi
│   ├── cal.vi
│   ├── case --- calculator.vi
│   ├── case selector.vi
│   ├── debugging.vi
│   ├── for loop.vi
│   ├── pass_and_fail.vi
│   ├── traffic light using flat sequence.vi
│   └── while loop.vi
│
├── 📁 Math & Data Structures
│   ├── Array_operation.vi
│   ├── clusters.vi
│   ├── FACTORIAL SUB VI.vi
│   ├── pallindrome.vi
│   └── permutation.vi
│
├── 📁 File I/O
│   ├── csv file.vi
│   ├── csv read.vi
│   ├── csv write.vi
│   ├── cSv.csv
│   ├── FILE ONLY READ.vi
│   ├── file read and write.vi
│   ├── read binary.vi
│   ├── read sine to file data.vi
│   ├── sine to file (csv).vi
│   └── write binary.vi
│
├── 📁 Signals & Visualization
│   ├── Signal generator.vi
│   ├── waveform control.vi
│   └── waveform_chart.vi
│
├── 📁 Audio & Speech
│   ├── audio_input.vi
│   ├── talking tom.vi
│   └── text_to_speech.vi
│
├── 📁 Games & UI
│   ├── catch me if u can.vi
│   └── piano.vi
│
├── 📁 Introductory VIs
│   ├── Untitled 1.vi
│   ├── Untitled 2.vi
│   ├── Untitled 3.vi
│   ├── Untitled 4.vi
│   └── Untitled 5.vi
│
└── README.md
```

---

## 🤝 Contributing & License

Contributions, improvements, and additional sample VIs are welcome! Feel free to fork the repository, file issues, or submit pull requests.



## **The CHASE continues**