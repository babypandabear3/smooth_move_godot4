# smooth_move_godot4
Smooth Move for Godot 4

A smoothing helper node to solve jittering problem


Installation

copy smooth_move folder to project folder

Usage

- add a new node, select Smooth_Move2D / Smooth_Move3D as type
- add node that movement will be smoothing as Smooth_Move2D / Smooth_Move3D child
- set target_path for Smooth_Move2D / Smooth_Move3D to follow
- if target_path is empty, Smooth_Move2D / Smooth_Move3D will follow it's parent transform


Common Setup for 3D
- RigidBody3D
  - Smooth_Move3D 
    - MeshInstance3D
	
- CharacterBody3D
  - Smooth_Move3D 
    - MeshInstance3D


Common Setup for 2D
- RigidBody2D
  - Smooth_Move2D 
    - Sprite2D
	
- CharacterBody2D
  - Smooth_Move2D 
    - Sprite2D