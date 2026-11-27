# 🎸 Ultimate Bass Workstation & Professor BAI

Out of my passion to learn bass guitar this year, I vibecoded this application. It was built to help beginners and intermediate bassists like myself to master the bass guitar fretboard visually, shatter box-shape dependency, and build fluid modal fluency across a 24-fret neck.

**Built by SamDan**

---

## ✨ Core Features

### 1. Interactive 24-Fret Neck & Real-Time Audio Engine
- **Multi-Tuning Support:** Switch seamlessly between **4-String Standard (E-A-D-G)**, **5-String Standard (B-E-A-D-G)**, and **Drop-D (D-A-D-G)** in both **Upright (Vertical)** and **Horizontal (Sideways)** orientations.
- **Authentic Bass Synthesis:** Powered by **WebAudioFont (`0330` Electric Bass)** with elastic string vibration physics, slide/hammer-on articulation, and **9-pose custom anatomical hand animations**.
- **Web MIDI Support:** Plug in any USB or Bluetooth MIDI keyboard to play the bass engine with velocity sensitivity, answer drills, and watch notes map onto ergonomic fretboard positions in real time.

### 2. Structured Fretboard Mastery Strategies (`A – F`)
- **Strategy A — Full Scale Matrix Mapping:** Drill complete scale matrices across all 24 frets in Note Name or Tonic Solfa (`Do Re Mi`) notation.
- **Strategy B — Syllable Note Hunter:** Locate specific scale degrees across the neck.
- **Strategy C — Interval Vector Flashcard:** Master fretboard interval geometry.
- **Strategy D — Multi-String Focus:** Isolate any combination of strings (`B E A D G`) in **Fixed Key**, **Naturals Only (No `#/b`)**, or **Natural Chromatic (All 12 Notes)** modes.
- **Strategy E — Timed Root Hunter:** Beat the clock in single-string or full-neck root-finding rounds with auto-advancing streaks.
- **Strategy F — Blind Ear Training (Solfa & Song Key Finder):**
  - **Zero-Expo Blind Audio:** Plays reference cadences (`Doh–Sol–Doh`) and mystery notes with zero visual fretboard hints until you submit your answer.
  - **Progressive Solfa Tiers & Song Key Finder:** Train relative pitch from core anchors (`Doh, Fa, Sol`) up to full major (`Do–Ti`) and all 12 chromatic keys (`C` through `B`), with **Auto-Rotate** key modulation and multi-input support (touchscreen neck, Web MIDI keyboard, or live mic).

### 3. Academy Hub & Interactive Solfa Personality Guide
- **Live Key-Synced Cheat Sheets:** Instant interval decoders and scale references that dynamically adapt to your active Master Song Key.
- **Solfa Ear-Training Personality Guide:** Side-by-side breakdown of all 7 scale degrees (`Doh`–`Ti`) with emotional gravity, resolution pull, famous song anchors, and one-tap **`🔊 Hear`** audition buttons in your active key.

### 4. Professor BAI (Visual AI Bass Theory Guru)
- **Resilient Multi-Tier AI Cascade:** Powered by **Google Gemini (`gemini-3.5-flash-lite`)** with automatic failover to **Groq (`openai/gpt-oss-120b`)** and an offline theory fallback.
- **Automated Shape Boxes & Directional Vector Arrows:** Visualizes scale shapes, pentatonic boxes, harmonic symmetry, and interval connections (`-5/+5` Unisons, `-2/+2`, `-7/+7`, and `-12/+12` Octaves) with interactive layer filters (`All`, `Unisons`, `Octaves`, `Boxes`) and Slow-Mo playback (`0.5x`, `0.75x`, `1.0x`).
- **Pitch-Verified Accuracy:** Client-side diatonic pitch validation ensures every generated scale run and target drill snaps to true in-key notes and resolves cleanly to the tonic.
- **Built-In Accompaniment & Solo Sandbox:** Jam alongside synchronized Web Audio electric piano chords and drums with continuous **Loop** mode and **AI Bass Mute** for open-ended soloing.

### 5. 🎸 Live Rig (Physical Bass Companion Suite)
- **Harmonic-Locked Bass Tuner:** YIN/Autocorrelation pitch detector with 2nd/3rd harmonic locking for accurate low-B (`30.87 Hz`) and low-E (`41.20 Hz`) tuning via device microphone.
- **Hands-Free Mic Root Hunter & Fretboard Mirror:** Practice Strategy E hands-free with a physical bass while watching plucked notes light up on the virtual neck.
- **Instant Jam Backing Band:** One-tap electric piano and drum grooves across Gospel, Funk, Neo-Soul, Reggae, and Rock styles with an **Auto-Progression** generator.
- **Rhythm & Groove Pocket Meter:** Real-time transient onset analysis measuring whether your playing is dead on the beat, rushing, or laying back.

---

## 🚀 Quick Start
1. Open the deployed web app on mobile or desktop.
2. Tap **Initialize Sound** to unlock the Web Audio engine.
3. Optional: Tap **⚙ API** inside **Professor BAI** to add your free Google Gemini and/or Groq API keys (stored locally in your browser's `localStorage`).
   
