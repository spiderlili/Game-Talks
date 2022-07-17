Speakers: Sam Royall (Electric Square), Neil Hutchison (AlphaBlit), Matt Rubin (AlphaBlit)

# Overview
- Co-developing 'Detonation Racing' for Apple Arcade
- Using the DOTS architecture in Unity to develop a scalable system that played to the strengths of a wide range of device capabilities
- Vehicle handling implementation using the DOTS physics engine 
- How to leverage variable time-steps to support non-interactive sequences during gameplay
- Overview of an internally developed offline visibility culling system for reducing vertex bandwidth
- Overview of the performance reporting system that was utilised to ensure the release of a high-quality and high-performance title across the board of target devices on the Apple platform

# ECS 
- Entity worlds are load in place
- Archetype: a unique set of component types
- Chunks: entities of the same archetype are stored in chunks
- Chunks are 16 kilobytes in size
- Changing an Entity's Archetype is slow (structural change)
- Editor integration is poor (.e.g. can't click on an objet in scene view)
- Entity Debugger takes some acclimatisation

# Job System
- Race condition detection built-in
- cont: 933

https://reattendance.com/event-lobby/5884/session-stage