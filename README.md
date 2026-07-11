# REDPARSON GAME ENGINE

**A Safe Simulated 3D Game Engine & Creative Platform**

Built with **Three.js + Web Audio API** — Fully functional in the browser.

![Screenshot](assets/screenshot.png)
Tech StackThree.js (WebGL)
Web Audio API
Vanilla HTML/CSS/JS
Modular & Extensible Architecture

# REDPARSON Architecture

### Dictionaries/Methods for Data/Code in BPS

- **Bits Per Second Encoding**: Structured dictionaries for encoding and decoding operations in base44
- **Method Registry**: Comprehensive method repositories for data transformation and code execution
- **Base44 Conversion**: Efficient encoding/decoding of bitstream data at optimized BPS rates
- **Cross-Layer Translation**: Data/code methods optimized for performance across all architecture layers

### Safe AI Sim - AI Scene Generation(Modular)

**Safe AI Simulation Framework for High-Confidence 3D Asset Management and Rendering**

A robust, safety-first simulation engine designed to draw, identify, index, interlock, and interlink high-confidence / low-risk assets in 3D environments. Safe AI Sim optimizes object-to-scene composition using the **golden ratio** (φ ≈ 1.618) across the full graphics pipeline — from abstract class hierarchies to clip space and the active viewport.

---

## Overview

Safe AI Sim provides a complete architecture for creating trustworthy 3D simulations where every asset is continuously evaluated for confidence and risk. The system ensures that rendered scenes maintain structural harmony, visual balance, and semantic safety through golden-ratio-aware placement, interlocking, and interlinking of assets.

**Core Philosophy**: "Safe by Design" — every transformation, placement, and rendering decision is gated by multi-factor confidence scoring and risk assessment.

### Key Capabilities

- **Golden Ratio Scene Composition**: Automatic layout of objects, cameras, and lighting using φ-based proportions for aesthetic and structural harmony.
- **High-Confidence Asset Pipeline**: Real-time identification, indexing, validation, and risk scoring of 3D assets.
- **Interlocking & Interlinking**: Semantic and spatial relationship management between assets (physics, logic, and visual constraints).
- **End-to-End Pipeline Visibility**: Abstract classes → Scene Graph → World Space → View Space → Clip Space → Viewport.
- **Safety-First Rendering**: Only high-confidence, low-risk configurations are promoted to the active viewport.

---

## Architecture

### High-Level Layers

graph TD
    A[Abstract Classes & Domain Models] --> B[Asset Registry & Confidence Engine]
    B --> C[Golden Ratio Layout Optimizer]
    C --> D[Scene Graph Builder]
    D --> E[Spatial Interlocking Engine]
    E --> F[Semantic Interlinking Layer]
    F --> G[World → View → Clip Space Pipeline]
    G --> H[Risk-Gated Renderer]
    H --> I[Active Viewport & Simulation Output]

## Core Layers
- **MapLayer** — Terrain, Portals, Collision Shell
- **AssetLayer** — Models, Textures, Animations
- **SafetyLayer** — Red Bounding Cubes, Safe Zones, Rollback
- **TransformLayer** — Green Checkpoints, Rotation Vectors
- **RenderLayer** — Blue Wireframe, Clip Space, Debug

## Systems
- AI Scene Generation (Modular)
- Physics + Audio Synthesis
- Particle System
- Project Serialization (.red format)
- Safe Simulated CI/CD Pipeline

## Philosophy
"Build without fear" — Everything runs in a safe sandbox.

## ✨ Features

- Real-time 3D Viewport
- AI-Assisted Scene Generation
- Advanced Particle Editor
- Animation Timeline
- Sound Designer + Physics-based SFX
- Material & Texture System
- Full Project Save / Load / Export (.red)
- Safety Layer Simulation
- Responsive Dashboard

## 🚀 Quick Start

```bash
# Clone or download
npm install
npm start
