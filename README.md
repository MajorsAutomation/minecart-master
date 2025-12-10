# Minecart Master

Pixel-based input automation project exploring gameplay automation through visual signal detection.

## Overview

This project is a pixel-based input automation tool built to explore how far gameplay automation can be pushed using screen analysis and scripted inputs alone.

It does not read memory, modify game files, or interact with servers. All behavior is driven by on-screen analysis and simulated key presses.

## How It Works

The application watches for specific visual signals and reacts by triggering pre-defined input sequences. Multiple detection strategies are available to account for window scaling, color variance, and frame timing differences.

## Safety & Limitations

- No memory access
- No packet inspection or network interaction
- No persistence outside active runtime
- Accuracy depends on calibration and screen consistency

Users are responsible for complying with any applicable game rules.

## Setup & Usage

Detailed setup instructions are included in the ZIP archive.

Key configuration steps include:
- Window positioning
- Pixel signal calibration
- Speed and timing adjustment

## About the Project

I’m Sam — a self-taught developer who enjoys experimenting with automation, AI-assisted tooling, and system-level problem solving.

This project started as a simple question: 
Can a minigame be fully automated using only visual signals and scripted inputs?

Over time, it evolved into a ~10,000-line AutoHotkey application featuring multiple detection strategies and a guided setup process.

## Acknowledgements

This project was developed with the assistance of AI tools as a learning and productivity aid. All implementation decisions were tested and validated manually.

