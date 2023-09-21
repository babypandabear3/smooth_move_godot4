# smooth_move_godot4
Smooth Move for Godot 4

A smoothing helper node to solve jittering problem


Installation

copy smooth_move folder to project folder

Usage

- add a new node, select Smooth_Move3D as type
- add node that movement will be smoothing as Smooth_Move3D child
- set target_path for Smooth_Move3D to follow
- if target_path is empty, Smooth_Move3D will follow it's parent transform


Common Setup
- RigidBody3D
  - Smooth_Move3D 
    - MeshInstance3D
	
- CharacterBody3D
  - Smooth_Move3D 
    - MeshInstance3D
