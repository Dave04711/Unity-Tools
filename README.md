# Unity-Tools

A collection of custom editor tools for Unity, designed to streamline workflows and enhance productivity during game development. These tools were originally developed for internal use in my projects and are now made available as standalone, modular utilities.

## Tools Overview

### RAS – React Animation System

A lightweight system for triggering contextual reaction animations (e.g., hit reactions) without relying on Unity’s Animator Controller.  
Designed for 2D sprite sheet-based games.

---

### AIE – AI Editor *(WIP)*

A node-based tool for designing modular AI behaviors for NPCs using a custom graph interface.  
Currently in an early state – UI is implemented, backend logic under development.

---

### CEF – Custom Editor Foldout  

Creating custom editor inspectors often requires boilerplate code, especially for read-only or foldout fields. This tool simplifies that process.

**How it works:**
Just add the `[Foldout]` attribute to your fields – no need for a separate editor script.

---

### SSW – Scene Switch Window  

An editor window that allows developers to instantly switch between scenes in the project without using the hierarchy.  
Perfect for large projects with many test or gameplay scenes.

---

### RAC – Reverse Animation Context  

Adds a right-click context menu option for creating reversed versions of selected `AnimationClip`s.  
Great for adding rewind animations without duplicating timeline effort.

---

## Highlights

- Built for Unity 2021.3+ (tested on LTS)
- No external dependencies
- Each tool is independent and can be imported separately
- Designed to be lightweight, readable, and production-friendly
