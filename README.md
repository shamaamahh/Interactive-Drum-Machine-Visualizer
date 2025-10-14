# Interactive Drum Machine Visualizer

## Overview
For my Computer Music final project, I created an **interactive drum machine** in **Pure Data** inspired by the synthesizer we made in class. My original composition, titled **“Jungle Juice”**, serves as the foundation for this project.

This project combines **music creation**, **sample manipulation**, and **interactive visuals** to produce a dynamic audio-visual experience.

---

## Features

### Original Composition
- Cadence titled **“Jungle Juice”** composed for this project.
- Score generated as a **WAV file** using **MuseScore**, including MIDI sounds that were sampled to create specific instruments like **jam block** and **cowbell**.
- PDF of the score included in the zip file.

### Drum Machine Functionality
- **Live looping** of the main cadence.
- Ability to add **auxiliary sounds** and samples (both class-provided and custom).
- Uses a **16-second synthesizer** to play samples.

### Interactive Visuals (via GEM)
- Each drum sound triggers a **corresponding shape** and color in the visualizer.
- Shapes include **squares, circles, and triangles**, arranged like a **visual drum set layout**.
- Shapes are positioned using the **`translate`** object in GEM.
- Each shape/sound relationship requires a new **gemhead**.
- Optional **particle visualizer** included (YouTube tutorial credited).
- Visuals **dynamically respond to the music**, enhancing the interactive experience.

---

## Installation & Setup
1. Install **Pure Data (Pd)** with the **GEM package**.
2. Open **`main.pd`** to start the drum machine.
3. Ensure the **samples folder** is in the same directory as the patch.
4. Open **`visual.pd`** to see the interactive visualizer.
5. (Optional) Switch between standard shapes and particle visualization in the patch.

---

## Usage
- Press **Play** in `main.pd` to start the drum loop.
- Trigger different sounds via the drum machine interface to see corresponding visual shapes.
- Experiment with auxiliary sounds and particle mode for a fully interactive experience.

---

## Credits
- Particle visualizer tutorial: YouTube (credit included in patch).
- **MuseScore** for generating WAV files from MIDI composition.

---

## Notes
- Each shape/sound relationship requires a new **gemhead** in GEM.
- Shape positions are controlled with **`translate`** objects to maintain a visually coherent drum set layout.
- Designed as a **fun, interactive exploration of music visualization** and represents my final project for the course.
