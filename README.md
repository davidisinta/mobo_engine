# Mobo 2D Game Engine Overview

A 2D game engine designed for easy integration of game components. It supports input handling, rendering, animation, sound, resource management, and scene management. The engine uses a component-based architecture for flexibility and efficiency.

## Website

## Key Features
- **2D Game Focus**: Built specifically for 2D games.
- **Modular Architecture**: Components can be added, extended, or replaced.
- **Scene Management**: Game objects organized in a scene tree for efficient management.
- **Animation**: Supports sprite-based animations.
- **Sound Integration**: Manages sound effects and music.
- **Input Handling**: Handles user inputs in various scenes.
- **Resource Management**: Efficiently loads and manages assets.

## Component Overview

- **Scene Management**  
  SceneTree: Organizes and manages game objects in a hierarchical structure.

- **Input Handling**  
  InputHandler, Inputable: Handle scene-specific inputs.

- **Rendering**  
  Renderable: Represents objects that need to be rendered (e.g., sprites, maps).

- **Resource Management**  
  ResourceManager: Handles loading and optimizing game assets (e.g., images, sounds).

- **Animation**  
  AnimationSequences, Frame: Store and manage animation sequences and frames.

- **Sound**  
  Sound: Handles sound effects and music playback.

- **Game Objects**  
  GameObject: Represents in-game entities (e.g., sprites, UI elements).

- **Scriptable Components**  
  ScriptComponent, ProjectileScriptComponent: Adds custom behaviors to game objects.

## Game Object Components
- **Updateable**: Handles updates for a scene or object.
- **IComponent**: Interface for components that define game object behaviors and appearance.
