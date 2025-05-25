[Live Demo](https://sankalp1999.github.io/swarm-sim/swarm-simulation.html)

# Swarm Intelligence Simulation

### Boids vs Predator with Evolution

> **Boids** are artificial life forms following three simple rules:

- **Alignment** - Match direction with neighbors
- **Cohesion** - Stay close to the group
- **Separation** - Avoid collisions

The term "Boid" is short for "bird-oid object." The simulation and its underlying principles were developed by Craig W. Reynolds in 1986.

A **predator** hunts the swarm, forcing evolution. Boids that survive reproduce, passing on genetic traits like speed and evasion abilities. Successful boids automatically reproduce every ~15 seconds.

**Key Features:**

- Real-time evolution across generations
- Self-attention mechanism for global awareness
- Interactive predator control (arrow keys)
- Emergent survival strategies
- Advanced visual effects: Particle trails, glowing obstacles
- Enhanced mobile UX: Haptic feedback, swipe gestures (cycle camera, toggle hunt mode/predator, reset camera)
- Emergent behaviors: Panic scatter, V-formation escape
- Environmental obstacles: 3D spheres boids and predator avoid
- New "Ambush" predator hunting strategy
- Performance optimizations: Spatial grid for O(1) neighbor lookup

Watch as simple rules create complex, lifelike behaviors. Welcome to the swarm.