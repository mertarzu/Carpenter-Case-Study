# Carpenter Game Case Study

## Overview
A simple multiplayer carpenter workshop simulation built in Unreal Engine 5.7.

Players:
- Produce objects from the carving machine
- Paint them on the painting workbench
- Deliver them to complete orders
- Share a common budget

## Multiplayer
- Built and tested using Listen Server (4 players)
- Shared state handled via GameState
- Server-authoritative gameplay logic
- Replication used for:
  - Object spawning
  - Object color changes
  - Order system
  - Budget system

## Controls
- E → Interact (Pickup / Drop / Use)

## Notes
- Focus was on gameplay systems and network architecture

