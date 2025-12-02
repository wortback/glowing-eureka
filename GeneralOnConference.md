## Core Themes

* Simulation in Medicine
* Immersive VR/AR systems for surgical procedures
* Collaborative interactive solutions
* Novel algorithms for visualisation (e.g., new shaders to visualise tumor growth)
* New interaction techniques and interfaces
* Realistic physics simulation

## Aligning VR Eye Surgery Simulator Paper with VCBM Expectations

1. **Medical motivation**: training need in ophthalmic surgery and what sets it appart from other surgeries (e.g., small size of the eye, etc.). What skills we are adressing? Or are we gonna stand out because it's a simulation of a rare operation (I think we need to emphasise this aspect and tie it to the retinal implant research to make it more relevant).

2. **Highlighting novel simulation techniques**: we need something that sets the sim appart. I think the fact that we target Meta Quest 3 is already a novel aspect, as OssoVR doesn't deliver ophthalmic mudules and other ophthalmic sims like EyeSi are not VR in the sense of standalone VR.

3. **User Study**: must be with experts and medical students alike. Most target usability, repceived usefulness, and realism. 
    - Realism: realistic physics simulation with volumetric meshes?
    - Realism: gotta work on those shaders or textures harder this time
    - Realism: tools and eyes should be remodelled

---
### Side Comments

* Maybe we can use hand tracking. If we trace three fingers (thumb, pointing, and middle), they spawn a triangle. If the triangle's area A is less than a certain threshold value, we know that the user is holding something (this way users can even hold the real instruments while using the sim) between their fingers. 

