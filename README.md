# Unity-Tools

A collection of custom editor tools for Unity, designed to streamline workflows and enhance productivity during game development. These tools were originally developed for internal use in my projects and are now made available as standalone, modular utilities.

## Tools Overview

### RAS – React Animation System

A lightweight system for triggering contextual reaction animations (e.g., hit reactions, stumbles, knockdowns) without relying on Unity’s Animator Controller.  
Designed for 2D sprite sheet-based games.

**Key Features:**
- Avoids Animator complexity
- Trigger reactions via code or events
- Supports modular animation playback with custom rules

---

### AIE – AI Editor *(WIP)*

A graph-based visual editor for building modular AI behaviors for NPCs.  
Built on Unity’s GraphView API, it shares its core structure with RAS.

**Current status:** UI and visual graph logic implemented – logic system still under development.  
**Use case:** Design routines and AI logic without hardcoding transitions or conditions.

---

### Pathfinding Tool

A utility that generates and bakes navigation graphs used for pathfinding (grid-based, hierarchical, etc.).  
Also allows for manual editing and inspection of generated graphs directly in the editor.

**Key Features:**
- Automatic graph generation from tilemaps or level geometry
- Manual override of node connections
- Supports integration with external pathfinding systems

---

### CustomEditor Utilities

Creating custom editor inspectors often requires boilerplate code, especially for read-only or foldout fields. This tool simplifies that process.

**How it works:**
Just add the `[Foldout]` attribute to your fields – no need for a separate editor script.

**Benefits:**
- Faster creation of debug-friendly inspectors
- Clean separation of grouped values
- Works out-of-the-box once imported

---

## Why These Tools?

Each tool was built to solve a real production issue during gameplay and AI system implementation:
- **RAS**: Simplified dynamic reaction animations without animator overhead
- **AIE**: Designer-friendly AI system authoring (coming soon)
- **Pathfinding Tool**: Custom graphs adapted to unique level layouts
- **CustomEditor**: Inspector quality-of-life improvements
