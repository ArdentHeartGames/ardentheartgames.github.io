---
layout: page
title: Features
permalink: /features/
---

# Features

<img src="assets/images/engine-splash.png" alt="Ardent Heart Engine" style="max-width: 279px; width: 100%; height: auto;" />

Discover what the Ardent Heart Editor can do for your game development workflow.

## Core Editor Features

### Visual Scene Editor

- **Drag-and-drop interface** for placing and arranging game objects
- **Multi-selection and batch operations** for efficient scene composition
- **Grid and snap tools** for precise positioning
- **Layering system** for organizing scene elements
- **Zoom and pan controls** for navigation of large scenes

### In-Editor Game Runtime View

- **Instant testing** - Play your game directly within the editor
- **Real-time updates** - See changes immediately without rebuilding
- **Debugging view** - Console output and performance monitoring
- **Quick iteration** - Rapid test-modify-test workflow

### Asset Management

- **Centralized asset browser** with search and filtering
- **Asset preview** for quick identification
- **Import support** for common image, audio, and data formats
- **Asset organization** with folders and tags

### Script Editor

- **TypeScript support** with full type checking
- **Syntax highlighting** and code completion
- **Error detection** and linting
- **Script attachment** to game objects and components

### Inspector Panel

- **Property editing** for game objects and components
- **Real-time updates** reflected immediately in the game view
- **Custom property types** including colors, vectors, and enums
- **Component management** - add, remove, and configure components

## Current Components

The editor currently includes these built-in components:

### Visual Components
- **Sprites** - 2D graphics with texture support
- **Text** - Rendered text with font and styling options
- **Animations** - Sprite animations and property tweening

### Interactive Components
- **Buttons** - Clickable UI elements with event handling

### Structure Components
- **Prefabs** - Reusable game object templates
- **Scenes** - Multiple scene support with transitions

### Logic Components
- **Scripting** - TypeScript-based game logic and behaviors

### Audio Components
- **Audio** - Sound effects and music playback via Howler.js integration
- **Multi-channel playback** with volume and pitch control

### Physics Components
- **Physics Bodies** - 2D physics simulation via Matter.js integration
- **Collision detection** and response
- **Rigid body dynamics** with mass and velocity

## Build & Export

### Build Targets

Export your games to multiple platforms:

- **Web** - HTML5 games that run in any browser
- **Electron** - Cross-platform desktop applications (Windows, macOS, Linux)
- **Tauri** - Lightweight, secure desktop builds using Rust

### Build Features

- **Optimized builds** with minification and tree-shaking
- **Asset bundling** for efficient loading
- **Development and production modes**
- **TypeScript compilation** with type checking

## Plugin System

### Plugin Installation

- **Git Repository Plugins** - Install plugins directly from Git URLs
- **Steam Workshop** - Browse and install community plugins (primary platform)
- **Steam DLC** - Official plugin releases and expansion packs

### Plugin Capabilities

- **Custom components** - Add new component types
- **Editor extensions** - Extend the editor's functionality
- **Workflow tools** - Automate common tasks
- **Asset processors** - Custom import and optimization pipelines

## Planned Features (Roadmap)

### Visual Editors (Coming Soon)

- **Animation Editor** - Visual timeline-based animation creation
- **Visual Scripting** - Node-based scripting system for non-programmers
- **Particle System Editor** - Visual particle effect designer

### 3D Support (In Development)

- **ThreeJS Integration** - 3D rendering alongside 2D content
- **3D Model Import** - Support for GLTF, FBX, and OBJ formats
- **3D Scene Editor** - Tools for positioning and manipulating 3D objects
- **Lighting & Materials** - PBR materials and advanced lighting

### AI-Assisted Development (Planned)

- **Local LLM Integration** - Use local AI models for development assistance
- **EditorAPI Interaction** - AI can perform common editor tasks
- **Smart Suggestions** - Context-aware code and design recommendations
- **Workflow Automation** - AI-powered task automation

## Requirements

To use the Ardent Heart Editor:

- **pnpm** - Package manager (required for project dependencies)
- **Rust** - Required for Tauri platform builds (optional if only targeting Web/Electron)

## Platform

The Ardent Heart Editor will be exclusively available on **Steam**:

- **Early Access**: Q1 2026 (could be sooner)
- **Before Early Access**: Invite-only access for early adopters
- **Distribution**: Steam exclusive from Early Access launch

---

[Learn More About the Editor](../about/) | [View the Roadmap](../roadmap/) | [Read Latest Updates](../updates/)
