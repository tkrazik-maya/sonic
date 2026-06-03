# Sonic

**Captured Maya — sound.**

An AI orchestra built from vinyl. A Kirtan system for live devotional performance. Two instruments, one infrastructure.

## What it is

Vinyl records are the corpus. AI learns their timbre and generates new players from that material. You conduct via Ableton Push 2.0 — setting direction, energy, structure — while the AI handles orchestration moment to moment.

The Kirtan system is an offshoot: a drone engine, a rhythmic cycle, and an AI call-and-response that answers your melodic lead.

## Hardware

- Laptop
- Audio interface
- Ableton Push 2.0
- Shure mic
- MIDI synth (drone engine)
- Vinyl records (the corpus)

## Software stack

- Ableton Live 11 Suite
- RAVE + nn~ (Max for Live) — core AI engine, trained on vinyl corpus
- Demucs — local stem separation (drums, bass, melody, other)
- Magenta — MIDI generation and melodic call-and-response
- Max for Live — custom conductor devices, Push 2.0 mapping

## Structure

```
docs/          — architecture, signal chain, kirtan spec, session notes
python/        — Demucs workflow, utility scripts
max/           — Max for Live device patches
samples/       — gitignored (audio files)
models/        — gitignored (trained RAVE models)
```

## Modes

**Orchestra mode** — full AI ensemble, vinyl-trained players, Push 2.0 as conductor  
**Kirtan mode** — drone + tala + AI call-and-response, mic-driven, meditative

## Part of

[Captured Maya LLC](https://github.com/tkrazik-maya) · Entity filed March 28, 2026
