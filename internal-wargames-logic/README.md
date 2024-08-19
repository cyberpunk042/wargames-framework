# Internal Wargames Logic

## Overview

The Internal Wargames Logic branch contains the core gameplay mechanics that define the wargames. It manages player actions, resource flows, conflict resolution, and territory control, ensuring that the game is engaging, balanced, and consistent.

## Components

1. **Player and Group Management**
   - **Player**: Manages individual player actions, resources, and territories.
   - **Group**: Manages group dynamics, including resource distribution and collective decisions.
   - **ResourceManager**: Handles the player’s or group’s resources, including accumulation, deduction, and transfer.
   - **OwnershipManager**: Manages ownership and territory control, including claiming and defending locations.

2. **Location and Territory Control**
   - **Location**: Represents a location on the game map, with associated resources, ownership, and challengers.
   - **OwnershipManager**: (Shared with Player and Group Management) Handles the control and transfer of territories.

3. **Conflict and Resolution**
   - **Conflict**: Manages conflicts between players or groups, including declaring war and resolving conflicts.
   - **ConflictResolutionStrategy**: Provides different strategies for resolving conflicts, such as direct battle, negotiation, or forming alliances.

4. **Resource Management**
   - **Resource**: Represents resources within the game, including their generation, accumulation, and trade.
   - **ResourceScanner**: Allows players to scan locations for available resources, determining if they should be claimed or contested.

## Purpose

The Internal Wargames Logic branch is the heart of the game, where all the gameplay mechanics are implemented. It ensures that the game is challenging, strategic, and fair, providing players with a rich and immersive experience.