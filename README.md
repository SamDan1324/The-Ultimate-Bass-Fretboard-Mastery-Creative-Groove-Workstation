# The Ultimate Bass Fretboard Mastery & Creative Groove Workstation

# 🎸 Ultimate Bass Workstation & Professor BAI

Out of my passion to learn bass guitar this year, I vibecoded this application. It was built to help beginners and intermediate bassists like myself to master the bass guitar fretboard visually, shatter box-shape dependency, and build fluid modal fluency across a 24-fret neck.

**Built by SamDan**

---

## ✨ Core Features

### 1. Interactive 24-Fret Neck & Real-Time Audio Engine
- **Multi-Tuning Support:** Switch seamlessly between **4-String Standard (E-A-D-G)**, **5-String Standard (B-E-A-D-G)**, and **Drop-D (D-A-D-G)** in both **Upright (Vertical)** and **Horizontal (Sideways)** orientations.
- **Authentic Bass Synthesis:** Powered by **WebAudioFont (`0330` Electric Bass)** with elastic string vibration physics, slide/hammer-on articulation, and **9-pose custom anatomical hand animations**.
- **Web MIDI Support:** Plug in any USB or Bluetooth MIDI keyboard to play the bass engine with velocity sensitivity and watch notes map onto ergonomic fretboard positions in real time.

### 2. Professor BAI (Visual AI Bass Theory Guru)
- **Resilient Multi-Tier AI Cascade:** Powered by **Google Gemini (`gemini-3.5-flash-lite`)** with automatic failover to **Groq (`openai/gpt-oss-120b`)** and an offline theory fallback.
- **Automated Shape Boxes & Directional Vector Arrows:** Visualizes scale shapes, pentatonic boxes, harmonic symmetry, and interval connections (`-5/+5` Unisons, `-2/+2`, `-7/+7`, and `-12/+12` Octaves) with interactive layer filters (`All`, `Unisons`, `Octaves`, `Boxes`) and Slow-Mo playback (`0.5x`, `0.75x`, `1.0x`).
- **Pitch-Verified Accuracy:** Built-in client-side diatonic pitch validation ensures every generated scale run and target drill snaps to true in-key notes and resolves cleanly to the tonic.
- **Built-In Accompaniment & Solo Sandbox:** Jam alongside synchronized Web Audio electric piano chords and drums with continuous **Loop** mode and **AI Bass Mute** for open-ended soloing.

### 3. Structured Fretboard Mastery Strategies (`A – E`)
- **Strategy A — Full Scale Matrix Mapping:** Drill complete scale matrices across all 24 frets in Note Name or Tonic Solfa (`Do Re Mi`) notation.
- **Strategy B — Syllable Note Hunter:** Locate specific scale degrees across the neck.
- **Strategy C — Interval Vector Flashcard:** Master fretboard interval geometry.
- **Strategy D — Multi-String Focus:** Isolate any combination of strings (`B E A D G`) in **Fixed Key**, **Naturals Only (No `#/b`)**, or **Natural Chromatic (All 12 Notes)** modes.
- **Strategy E — Timed Root Hunter:** Beat the clock in single-string or full-neck root-finding rounds with auto-advancing streaks.

### 4. 🎸 Live Rig (Physical Bass Companion Suite)
- **Harmonic-Locked Bass Tuner:** YIN/Autocorrelation pitch detector with 2nd/3rd harmonic locking for accurate low-B (`30.87 Hz`) and low-E (`41.20 Hz`) tuning via device microphone.
- **Hands-Free Mic Root Hunter & Fretboard Mirror:** Practice Strategy E hands-free with a physical bass while watching plucked notes light up on the virtual neck.
- **Instant Jam Backing Band:** One-tap electric piano and drum grooves across Gospel, Funk, Neo-Soul, Reggae, and Rock styles with an **Auto-Progression** generator.
- **Rhythm & Groove Pocket Meter:** Real-time transient onset analysis measuring whether your playing is dead on the beat, rushing, or laying back.

---

## 🚀 Quick Start
1. Open the deployed web app on mobile or desktop.
2. Tap **Initialize Sound** to unlock the Web Audio engine.
3. Optional: Tap **⚙ API** inside **Professor BAI** to add your free Google Gemini and/or Groq API keys (stored locally in your browser's `localStorage`).

### Creative Groove Sandbox
- Native P-Bass Synth: Web Audio API synthesis creating an organic wooden pluck clack completely offline.
- Drum Sequencer: Loops Funk, Jazz, or Hip-Hop beats with an adjustable BPM slider.
- Smart Evaluator: Map custom fills onto a grid to generate a masterclass audit analyzing your harmony, rhythmic spacing, and fretboard efficiency.

## Installation & Usage
This entire application is completely self-contained and hosted live for instant access.

- Play Online Instantly: You can access the workstation immediately in your browser via the live web application linked in the repository description.
- Install to Mobile Home Screen: Open the live website link on your mobile phone, tap your browser's share or settings button, and select "Add to Home Screen" to install it natively as a distraction-free application.
- Run Locally Offline: Alternatively, you can download the `index.html` file from this repository and double-click it to run the entire workspace locally on any desktop or mobile device with zero internet connection required.

