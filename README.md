# 🍕 Food Delivery Game

## 📖 Overview
**Food Delivery** is a 2D game developed in **Godot Engine (v4.4)** that simulates the role of a food delivery driver.  
The player must pick up orders from the restaurant and deliver them to the correct houses to earn points.  
The game integrates **AI-driven motivation** to guide and encourage the player during gameplay.

**Target Platform:** Web (HTML5 Export)

---

## 🎮 Gameplay
- **Player Character:**  
  Implemented with `CharacterBody2D` and `Node2D`, allowing smooth movement (Up/Down/Left/Right).

- **Restaurant & Orders:**  
  Player collects orders (Pizza, Burger, Sandwich) using an `OptionButton` menu.

- **Delivery System:**  
  Orders must be delivered to the assigned house (Home1..Home5).

- **Scoring System:**  
  - ✅ Correct delivery → score increases (Base + Speed + Combo).  
  - ❌ Wrong delivery or no order → score decreases.

---

## 🗺️ World & Levels
- **TileMap:** Custom-designed to represent a small city with restaurants, houses, and roads.  
- **Levels:**  
  - Level 1 → Small city with basic roads and houses.  
  - Level 2 → Expanded city with more houses and cars.  
- **Collision Methods:** Prevent out-of-bounds movement by blocking map borders and street sides.

---

## 🤖 AI Integration
- Integrated with **NobodyWhoChat API** for motivational AI interaction.
- AI provides:  
  - Initial instructions for picking up orders.  
  - Random encouragement messages at intervals.  
  - Final congratulatory message once maximum tasks are completed.  
- Chat system structured with `GridContainer` and `VBoxContainer` for message handling.

---

## 🎨 Design & UI
- **HUD:** Dynamic score counter.  
- **Menu System:** `OptionButton` for choosing order types (Pizza, Burger, Sandwich).  
- **Animations:** Smooth character movement animations.  
- **Background Music:** Enhances immersion during gameplay.  

---

## 🛠️ Development Stack
- **Engine:** Godot (v4.4)  
- **Language:** GDScript  
- **AI API:** NobodyWhoChat  
- **Export Target:** HTML5  

---

## 👥 Team Members
- **Lara Taweel** → Documentation & Testing  
- **Osama AbuReesh** → Game Development & Documentation  
- **Noorhan Kusa** → Game Development, AI Integration & Design  
- **Emad Almasri** → Design & AI Integration  
- **Abdullah Khdair** → Design & Character Animations  
