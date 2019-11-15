## Welcome to Chun Chung Chan's personal portfolio.

### Introduction
I recently graduated from University of California - San Diego with a Bachelor degree in Mathematics and Computer Science. My course works range from lower division microbiology, chemistry, physics, calculus, through upper divison computation theory, computer graphic, probability theory, graph theory, exposure to machine learning, parallel programming and image processing, all to way to graduate course in animation and physic simulation. I have also joined the UCSD undergraduate research program. From this program, I have learnt the valuable skill of conducting research. All of my knowledges are combined toward one purpose: to recreate reality in a simulated envirnoment. I strongly believe that in our near fufure, artificial intelligence and augment reality can integrate into our society homogenously, erasing the boundary of what is real.

### More about me as a Person
I am a logical person. Perhaps too logical. I often try to convert everything into number in a utilitarianism way. I love everything that can be expressed in logical expression, like math and code. This doesn't mean I am a boring person (at least I don't think myself being too boring). I enjoy traveling. Seeing human cultural heritage put a warmth feeling into my heart as to how far our civilization has come. I also like gaming. I have poor reaction time so I often play games that are much more strategic, like Total War and World of Warships. I like watching anime also. Clannad is my favorite as it tells a beautiful story of family bond.

### Course Projects
As a primary math student, I have less project based courses so my projects might be embarrassingly lack in variety, but their quality is no less than any engineering students. Course work projects are generally small and require only 2 - 3 weeks to finish. Since they involve rather elementary software design, I list them based on concept involved. Note that uploading actually code from course work is forbidden by academic integrity pledge (perfect excuse for not showing anyone of my poorly written code, am I right?).

Documentation such as args and return of a function, error handling, side effect etc.

Bit Operation in ARM assembly using AND, ORR, XOR, ASR, LSR etc.

Debugging using GDB and Valgrind.

Implement get_opt() for command option.

Implement trie data structure and Red-Black Tree data structure.

Implement graph and k-core decomposition.

LU decomposition, Gauss-Seidel method, hermite interpolation, and various other numerical method.

Various algorithms from graph search, greedy, divide and conquer, dynamic programming.

Camera projection, depth buffering, affine transformation, phong shading, texture mapping.

Bump mapping, normal mapping, model loading, cube mapping.

Catmull Rom, bezier and B-sphine.

Skeleton, skinning, rigging, morphing, keyframe extrapolation, inverse kinematics.

Spring particle system of cloth simulation.

Ray tracing, radiosity, MSAA, depth of field, motion blur.

### Particle simulation
When I was in UCSD, I explored into particle simulation. My first project in particle system is an extension to my course project in computer graphic. In this project, Cherry Blossom, is a real time scene that generated 10,000+ flowers on a tree, with each petal having their own movement. The flowers are randomly generated on the tree with a distribution that form a hollow half sphere on the tree. For each frame, random petals will be dequeued and begin falling from the tree. During the fall, the petals will perform collision check against the tree and "avoid" it with a force pushing the petals to the side using the tangent vector. In order to generate large amount of particle, an OpenGL technique call instancing is used to reduce the number of draw call to only once.
