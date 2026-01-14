---
layout: page
title: About
permalink: /about/
---

<div style="text-align: center; margin-bottom: 2rem;">
  <h1 style="color: #e6edf3; margin-bottom: 0.5rem;">About Ardent Heart Editor</h1>
  <p style="color: #8b949e; font-size: 1.1rem;">A lightweight, feature-rich game development tool designed to make game creation accessible and enjoyable.</p>
</div>

{% include free-to-play-badge.html %}

<div class="feature-grid">
  <div class="feature-card">
    <h3>🎯 Lightweight & Efficient</h3>
    <p>Fast, responsive interface without unnecessary overhead</p>
  </div>
  <div class="feature-card">
    <h3>⚡ Feature-Rich</h3>
    <p>Comprehensive toolset for 2D (and future 3D) game development</p>
  </div>
  <div class="feature-card">
    <h3>🔌 Extensible</h3>
    <p>Plugin architecture with Git repos and Steam Workshop integration</p>
  </div>
</div>

## Licensing

The editor is **free to use** for:
- **Solo developers** - Individual creators working independently
- **Indie teams** - Development teams with 10 or fewer members

For larger studios or commercial teams exceeding 10 members, licensing terms will be announced closer to the Early Access launch.

## Overview

### Architecture

The Ardent Heart Editor is built around three core principles:

1. **Lightweight & Efficient** - Fast, responsive interface without unnecessary overhead
2. **Feature-Rich** - Comprehensive toolset for 2D (and future 3D) game development
3. **Extensibility** - Plugin architecture with Git repos and Steam Workshop integration

### Key Components

- **Scene Editor** - Visual layout and composition of game scenes
- **In-Editor Game Runtime View** - Test your game instantly without leaving the editor
- **Asset Manager** - Centralized management of sprites, audio, and other resources
- **Script Editor** - TypeScript code editor with syntax highlighting
- **Inspector Panel** - Property editing for game objects and components

## Technology Stack

### Editor Platform

- **Electron** - Cross-platform desktop application framework
- **Vue.js** - Reactive UI framework for the editor interface
- **TypeScript** - Type-safe development environment

### Game Runtime

Games created with Ardent Heart Editor are built using:

- **TypeScript** - Type-safe game scripting
- **PixiJS** - Hardware-accelerated 2D WebGL renderer
- **Howler.js** - Audio engine (wrapped for easy integration)
- **Matter.js** - 2D physics engine (wrapped for seamless use)
- **ThreeJS** (coming soon) - 3D graphics capabilities

### Build Targets

Export your games to multiple platforms:

- **Web** - Deploy to any web server
- **Electron** - Standalone desktop applications
- **Tauri** - Lightweight, secure desktop builds using Rust

## Current Features

The editor currently includes components for:

- **Sprites** - 2D graphics and textures
- **Text** - Rendered text elements
- **Buttons** - Interactive UI elements
- **Animations** - Sprite and property animations
- **Prefabs** - Reusable game object templates
- **Scenes** - Multiple scene management
- **Scripting** - TypeScript-based game logic
- **Audio** - Sound effects and music via Howler.js
- **Physics** - 2D physics simulation via Matter.js

## Plugin System

Extend the editor's functionality through plugins:

- **Git Repository Plugins** - Install plugins directly from Git repos
- **Steam Workshop** - Primary distribution platform for community plugins
- **Steam DLC** - Official plugin releases and expansions

The plugin system allows the community to create and share custom components, tools, and workflow enhancements.

## Requirements

To use the Ardent Heart Editor, you'll need:

- **pnpm** - Package manager for dependencies
- **Rust** - Required for Tauri builds (if targeting Tauri platform)

## Availability

The Ardent Heart Editor will launch as **Early Access** on Steam in Q1 2026 (could be sooner). Before the Early Access release, access is invite-only to ensure quality and gather focused feedback from early adopters.

**Distribution**:
- Available exclusively on Steam
- Steam Workshop for community plugins and extensions
- Optional premium plugins and DLC through Steam

## Open Source Strategy

Starting with major release 2.x.x, each new major version release will result in the previous major version becoming open-source:

- When 2.x.x is released → version 1.x.x will be open-sourced
- When 3.x.x is released → version 2.x.x will be open-sourced
- And so on for future major releases

**Note**: There is currently no established timeline for when version 2.x.x will be released. A timeline will be announced at a later date.

## Future: AI-Supported Workflow

We're planning AI-assisted development features that will allow developers to:

- Use **local LLMs** to interact with the EditorAPI
- Automate common development tasks
- Accelerate workflow with intelligent suggestions
- Maintain privacy with local AI processing

## Philosophy

We believe that game development tools should:

- **Stay lightweight** without sacrificing features
- **Reduce friction** between idea and implementation
- **Foster experimentation** through rapid iteration
- **Support the community** through extensibility and sharing
- **Remain accessible** to developers of all skill levels

---

[View our Features](../features/) | [Check the Roadmap](../roadmap/) | [Read Updates](../updates/)
