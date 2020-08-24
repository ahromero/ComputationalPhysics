### Anatomy of a Python Project

Project name

+ .git  this is created by your git repo
+ setup.py In case you want to install it. You can skip it but it is Ok if you use it.
+ notebooks/  Directory that contains your notebooks for the project and use your implementation
+ tests/  Offer some testing that shows the results of your implementation.
+ examples/  provide some examples where you show the flexibility of your code
+ doc/  provide documentation to us your implementation.
+ scripts/   runnable python files
+ project/  this is where your project is going to be
  - ```__init__.py``  This tells python this is a package
  - code.py  these are the different files you have created
  - subpc/  subpackages if you need them
  - data/   if you need data

+ requirements.txt a list of libraries you need to have before your package is used



### Project ideas

The following are general ideas that you can modify as you please but at the end, you have to submit a clear proposal (no more than one page). You can also propose an idea but you have to discuss it with me before it is accepted. Now, the projects below are flexible such that you can change them. You will have to work on the "goals of the project", the physics involved and how we could simulate the problem.

All projects involved a part where you solve the problem, a graphical part that shows the solution or show the dynamics and  a part where you can vay the conditions of the problem to see the effects.

+ Self avoiding random walk in 3 Dimensions with random objects disposed in a given domain.
+ Wave propagation on membranes (continuous) in 2D with simple objects.
+ Lennard Jones molecular dynamics in 2D and 3D with obstacles in fixed volume.
+ Model of electric discharge by using diffusion limited aggregation (with external fields)
+ Propagation of pulse in nonlinear media (modeled by balls and non linear springs)
+ The motion of asteroid 3753 Cruithne --Earth's second Moon? The near-Earth asteroid 3753 Cruithne is now known to be a companion, and an unusual one, of the Earth. This asteroid shares the Earth's  orbit, its motion 'choreographed' in such a way as to remain stable  and avoid colliding with our planet. This relationship was revealed in a paper by Paul Wiegert, Kim Innanen and Seppo Mikkola, and published in Nature on June 12, 1997.  However, Cruithne's path is much more complicated than simple satellite motion.  The aim of this project is to write a program to simulate the orbit of Cruithne and to investigate its stability.
+ Time dependent Schrödinger. Diffusion of wave  (particles) in moving wells.
+ Granular media in 2D. 2D rigid spheres with specific interaction and you need to simulate the behavior of the media with different conditions (shaking the bottom, expanding or compressing the walls).
+ Vibrations in Quasicrystals.
+ Monte Carlo simulation of the Heissenberg model in 3D.
+ Vibrations of sizable bars in 3D.
+ In a number of racing sports, it is advantageous to be alongside other competitors. In some cases, e.g. triathlon cycling and orienteering, this is against the "spirit" and competitors do not start in a group. A model for this process wasdeveloped several year ago in a JH project "Pack formation in cycling and orienteering" G.J.Ackland and D.Butler, Nature, 413, 127 (2001).There are similarities to shock wave physics, to shallow water waves, and to traffic flows where the leading edge of a feature moves more slowly than the material behind it.The model was applied in "The effect of pack formation at the 2005 world orienteering championships" G.J.Ackland Scientific Journal of Orienteering 17 12 (2005)Since then, huge amounts of data have been obtained in various events. In this project you will analyse this data, and use it to parameterize and improve on the Butler/Ackland model.The project will be entirely computational. You will write a code to simulate the pack formation process, and you will gather and format data from various online sources to test the model against.
+ Optimizing rapid exit on an stadium due to stampedes. In this project, you will have to create a geometry of a stadium and define the number of doors and the geometry of the door (dimensions, door type, etc) and you have to simulate the situation where attendees have to rush to the door and have to exit the door safely. Every attendee will be simulated as a circle in 2D and it will have a term that should define a maximum pressure.
+ Simulate a chaotic pendulum with different  conditions (double pendulum, triple pendulum, different masses, etc). The program should be able to plot also the trajectories of the masses as function of time (for example for a double pendulum, plot $\phi_1$ and $\phi_2$ (angles of the masses of each pendulum)  vs time. Study the conditions for periodicity and chaos in this problem.