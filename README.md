# project-scale

## Gameplay
* Classic Rogue-like. More Mystery dungeon-esque
* Minimum 3 boss encounters that scales with the player
  * Each encounter will move player to special room designed for the fight
  * Stick with simple designs for boss room, focus on environment rather than mechanics
* Adjust size of enemies normal, large
  * Each has special attributes
* Adjust size of player to be normal or large,
  * Increases attribute but also decreases attribute for risk/reward
  
## Theme
* **Scaling** a mountain. Boss at the top
* Reocurring boss that scales with player
* Player can scale enemies size up and down.


## Timeline
### Week 1
Implement basic Rogue-like mechanics.
* Movement
* Enemies
  * Basic AI
    * Random until Line of sight in view then chase
* Combat
  * Basic Combat
    * Subtract from HP
* Level generation (Goal is 1 hour or less gameplay loop)

### Week 2
* Hook Rust logic to Godot as renderer

### Week 3
* Enhance combat
  * Turn priority/order
  * Ranged options
  * Movement options
  * Random environment obstacle generation
  * Mechanic to heal
* Implement size scaling mechanic (Remove enemy scaling if scope too big)
  * Increase size of sprite + collision
  * Decide on attribute changes

### Week 4 (Vague for now)
* Polish only existing mechanics.

#### Stretch Goals
* Semi-strategic AI
* More than 3 reocurring boss encounters