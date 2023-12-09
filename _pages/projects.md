---
title: "Projects"
layout: default_big
sitemap: false
permalink: /projects/
---

## Projects

### Projects with Writeups / Presentations

<div class="row">

<div class="col-sm-12 col-md-6 col-lg-4">

#### APRL

![Go1 Quadruped]({{ site.url }}{{ site.baseurl }}/images/research/go1_grass.jpg){: .align-center width="100%" style="max-width:400px"}

I co-first authored this paper:

Deep reinforcement learning can enable robots to autonomously acquire complex behaviors, such as legged locomotion. However, RL in the real world is complicated by constraints on efficiency, safety, and overall training stability, which limits its practical applicability. APRL is a policy regularization framework that modulates the robot's exploration over the course of real-world training, striking a balance between flexible improvement potential and focused, efficient exploration. It enables a quadrupedal robot to efficiently learn to walk entirely in the real world within minutes and continue to improve and adapt to deifferent scenarios with more training where prior work saturates in performance. 

<a class="btn btn-primary" href="https://sites.google.com/berkeley.edu/aprl/" target="_blank">Project Website</a> <a class="btn btn-primary" href="https://arxiv.org/abs/2310.17634" target="_blank">Arxiv</a>

</div>

<div class="col-sm-12 col-md-6 col-lg-4">

#### ROAR_PY_RL

![ROAR_PY_RL]({{ site.url }}{{ site.baseurl }}/images/research/carla.jpg){: .align-center width="100%" style="max-width:400px"}

I led the reinforcement learning research effort of autonomous racing in the [ROAR lab](https://roar.berkeley.edu/). We used the Stable Baseline library with the Carla simulator to train an SAC agent to drive autonomously in the Carla simulator. The agent is able to drive at 150 km/h in the simulator. The research effort is still ongoing and we're working towards a more stable and robust agent with new algorithms and environment modifications.

<a class="btn btn-primary" href="https://github.com/augcog/ROAR_PY_RL" target="_blank">Github Repo</a> <a class="btn btn-primary" href="https://roar.gitbook.io/roar_py_rl-documentation/" target="_blank">Read Documentation</a>

</div>

<div class="col-sm-12 col-md-6 col-lg-4">

#### ROAR_PY

![ROAR_PY]({{ site.url }}{{ site.baseurl }}/images/projects/roar_py.jpg){: .align-center width="100%" style="max-width:400px"}

I led the development of [ROAR lab](https://roar.berkeley.edu/)'s new control suite `ROAR_PY`: a streamable, gymnasium compatible control suite that unifies control of vehicles / reading of sensors in simulation and in real world for any robots. The project is currently in active development and is used by the lab for research and teaching.

<a class="btn btn-primary" href="https://github.com/augcog/ROAR_PY" target="_blank">Github Repo</a> <a class="btn btn-primary" href="https://roar.gitbook.io/roar_py-documentation/" target="_blank">Read Documentation</a>

</div>

<div class="col-sm-12 col-md-6 col-lg-4">
#### NanoGPT HW Set

![NanoGPT]({{ site.url }}{{ site.baseurl }}/images/projects/nanogpt.webp){: .align-center width="100%" style="max-width:400px"}

I (with two other friends) created a HW problem set around a lightweight GPT-2 implementation, [NanoGPT](https://github.com/karpathy/nanoGPT). This project is a rich, self-contained Jupyter notebook packed with tutorials and video resources to help students build a lightweight GPT implementation (including a BPE tokenizer, a GPT-2 model based on the Causal Transformer architecture) from scratch. This project also includes a lightweight autograder solution.

<a class="btn btn-primary" href="https://github.com/KevinLiu819/CS182_FP_Final">Github Repo</a>
</div>

<div class="col-sm-12 col-md-6 col-lg-4">

#### Rasterizer

![Rasterizer](https://www.quantumcookie.xyz/Opensourced-Study-Notes-Berkeley/CS184/proj1-rasterizer-writeup/images/task6-nearest-l0.png){: .align-center width="100%" style="max-width:400px"}

In this project, I implemented a simple 2d rasterizer that rasterizes mathematical expressions for shapes into pixel image buffers the implemented features include supersampling, hierarchical transforms, and texture(uv) mapping with antialiasing. The above image was rendered using my program.

<a class="btn btn-primary" href="https://www.quantumcookie.xyz/Opensourced-Study-Notes-Berkeley/CS184/proj1-rasterizer-writeup/" target="_blank">Read More</a>

</div>

<div class="col-sm-12 col-md-6 col-lg-4">

#### MeshEdit

![Meshedit](https://www.quantumcookie.xyz/Opensourced-Study-Notes-Berkeley/CS184/proj2-meshedit-writeup/images/task6_beetle_2.png){: .align-center width="100%" style="max-width:400px"} 

In this project, I built Bezier curves and surfaces using de Casteljau's algorithm, implemented algorithms to manipulate half-edge meshes, and implemented mesh up-sampling using loop subdivision. 

<a class="btn btn-primary" href="https://www.quantumcookie.xyz/Opensourced-Study-Notes-Berkeley/CS184/proj2-meshedit-writeup/" target="_blank">Read More</a>

</div>

<div class="col-sm-12 col-md-6 col-lg-4">

#### Pathtracer-1

![Pathtracer](https://www.quantumcookie.xyz/Opensourced-Study-Notes-Berkeley/CS184/proj3-1-pathtracer-writeup/images/task4_dragon_s1024_m5.png){: .align-center width="100%" style="max-width:400px"}

In this project, I implemented a CPU-based ray-traced renderer that can render complex scenes with multiple light sources and complex materials. The above image was rendered using my program.

<a class="btn btn-primary" href="https://www.quantumcookie.xyz/Opensourced-Study-Notes-Berkeley/CS184/proj3-1-pathtracer-writeup/" target="_blank">Read More</a>
</div>

<div class="col-sm-12 col-md-6 col-lg-4">

#### Pathtracer-2

![Pathtracer](https://www.quantumcookie.xyz/Opensourced-Study-Notes-Berkeley/CS184/proj3-2-pathtracer-writeup/images/CBdragon.png){: .align-center width="100%" style="max-width:400px"}

In this project, I further extended Pathtracer-1 to support Microfacet(rough-surface) materials, glass materials and mirror materials.

<a class="btn btn-primary" href="https://www.quantumcookie.xyz/Opensourced-Study-Notes-Berkeley/CS184/proj3-2-pathtracer-writeup/" target="_blank">Read More</a>
</div>

<div class="col-sm-12 col-md-6 col-lg-4">

#### ClothSim

![ClothSim](https://www.quantumcookie.xyz/Opensourced-Study-Notes-Berkeley/CS184/proj4-clothsim-writeup/img/task5_4_cloth.png){: .align-center width="100%" style="max-width:400px"}

In this project, I wrote a physics engine that simulates clothing materials. I also implemented shaders to render the cloth (and environments) in real-time.

<a class="btn btn-primary" href="https://www.quantumcookie.xyz/Opensourced-Study-Notes-Berkeley/CS184/proj4-clothsim-writeup/" target="_blank">Read More</a>
</div>

<div class="col-sm-12 col-md-6 col-lg-4">

#### ClothingMC

![ClothingMC]({{ site.url }}{{ site.baseurl }}/images/projects/clothing-mc.jpg){: .align-center width="100%" style="max-width:400px"}

In this project, we wrote a physics-based cloak simulation mod in Minecraft. The cloak is made of cubical meshes with $32 \times 20$ by size and is simulated by a mass-spring system.

<a class="btn btn-primary" href="https://www.quantumcookie.xyz/Opensourced-Study-Notes-Berkeley/CS184/final-proj-report/" target="_blank">Read Project Report</a>

</div>

<div class="col-sm-12 col-md-6 col-lg-4">

#### SIXT33N Voice-controlled Car

![SIXT33N]({{ site.url }}{{ site.baseurl }}/images/projects/eecs16b-car.png){: .align-center width="100%" style="max-width:400px"}

For this project, I built a voice-controlled car using an Launchpad SIXT33N. Me and my partner built the microphone circuit (band-pass) and the motor control circuit. We also wrote the code to control the car using the voice commands.

<a class="btn btn-primary" href="https://drive.google.com/file/d/1k19iq8nohCx-jr9pTyk09LCv2RZSBb-J/view?usp=sharing" target="_blank">View Video</a> <a class="btn btn-primary" href="https://quantumcookie.xyz/Opensourced-Study-Notes-Berkeley/EECS16B/Hand-on-lab-report.pdf" target="_blank">Read Project Report</a>

</div>

<div class="col-sm-12 col-md-6 col-lg-4">

#### Darbots

![Darbots Final Robot]({{ site.url }}{{ site.baseurl }}/images/projects/darbots_skystone_final.jpg){: .align-center width="100%" style="max-width:400px"}

I served as the team captain one year each for my high school FTC robotics team's varsity team (4100) and junior varsity team (5100). During my time there, I developed a suite of robotics libraries that supports asynchronous sensor updates, motion profiling, pure pursuit, object detection, etc. I also worked on the mechanical design of the robot, overall management of task assignment, journal keeping (for the engineering notebook), outreach, and presentation.

After I left the team, I volunteered at three FTC events in China, one time as an inspector and two times as the head referee.

<a class="btn btn-primary" href="https://youtu.be/UDJrd6aulxk?si=9wrcmNcuGuThwnbY" target="_blank">View Video</a>

</div>

</div>

### Projects without Writeups / Presentations

<div class="row">
<div class="col-sm-12 col-md-6 col-lg-4">

#### FPGA RISC-V CPU

![EECS151CPU]({{ site.url }}{{ site.baseurl }}/images/projects/eecs151cpu_diag_final.drawio.png){: .align-center width="100%" style="max-width:400px"}
![EECS151Board]({{ site.url }}{{ site.baseurl }}/images/projects/eecs151_z1_top_annotated.png){: .align-center width="100%" style="max-width:400px"}

For this project in EECS151LB, I implemented a 3-stage pipelined RISC-V CPU with the Verilog HDL. I tested this cpu on an AMD Xilinx PYNQ-Z1 board with a core clock frequency of 75MHz. The CPU supports the RV32I ISA as well as a subset of CSR instructions. The modifications made to the CPU that is different from the CS61CPU project are:

1. It is a synchronous-memory CPU, which means that the CPU has to prefetch instruction during the IF stage.
2. It includes a bunch of IO-mapped memory addresses that can be used to detect button presses, control LEDs, and control the audio output.
3. It includes an memory-mapped UART module that can be used to communicate with the host computer. A simple BIOS program provided by the class can be used to communicate with the host computer and write programs to the memory. Then the CPU can execute the program.
4. It includes an always-taken branch predictor.

</div>
<div class="col-sm-12 col-md-6 col-lg-4">

#### Pintos

![CS162 Panic]({{ site.url }}{{ site.baseurl }}/images/projects/cs162_panic.jpg){: .align-center width="100%" style="max-width:400px"}

For this project in CS162, I implemented part of an operating system called Pintos. The OS supports multi-threading, virtual memory, FFS file system, and user programs. The OS is written in C and x86 assembly.
The parts I implemented (with my team) are:
1. User program setup and syscall handling
   1. Parsing user program arguments and passing them onto the user stack
   2. Setting up stack and heap for the user program
   3. Initializing PCB and passing load information to the PCB
   4. Sleeping the parent process, passing info to the parent process waiting on the child process to load, and waking up the parent process
   5. Implementing `wait`, `exec`, `exit`, `sbrk`
   6. Implementing FPU context initialization, saving, and restoring
2. File System
   1. Implemented fs cache blocks using LRU eviction policy, free map, extensible inode, directory structures, and file structure
   2. Implemented file system calls `create`, `remove`, `open`, `close`, `read`, `write`, `seek`, `tell`, `filesize`, `mkdir`, `readdir`, `isdir`, `inumber`, `chdir`
3. Multithreading
   1. Implemented thread scheduling using priority scheduling
   2. Implemented thread `alarm` system call
   3. Implemented user level threads
      1. Designing and implementing thread control block
      2. Designing and implementing kernel level user thread trapping (to allow user threads to get terminated by the kernel)
      3. Implementing pthread library functions `pthread_create`, `pthread_exit`, `pthread_join`, `pthread_mutex_init`, `pthread_mutex_lock`, `pthread_mutex_unlock`, `pthread_sema_init`, `pthread_sema_up`, `pthread_sema_down`.

</div>

<div class="col-sm-12 col-md-6 col-lg-4">
#### UGBA 96 Clectricity
![Clectricity]({{ site.url }}{{ site.baseurl }}/images/projects/ugba96.png){: .align-center width="100%" style="max-width:400px"}

In UGBA 96, our team "Cookie Crumbs" developed a start-up pitch called Clectricity. Clectricity is an idea about an AI platform that connects small businesses with energy experts to help them achieve zero carbon emissions. We used value-proposition analysis, demos, revenue model analysis, target market analysis(competitors and market size), market differentiation analysis to pitch our idea to a panel of judges at the end of the class.

</div>
<div class="col-sm-12 col-md-6 col-lg-4">

#### CS61CPU
![CS61CPU]({{ site.url }}{{ site.baseurl }}/images/projects/cs61cpu.png){: .align-center width="100%" style="max-width:400px"}

For this project, I made a CPU design based on the RISC-V 32Bit Integer ISA. The final project is a fully 3-stage pipelined CPU with a 32-bit instruction set that supports RV32I ISA. 

</div>

<div class="col-sm-12 col-md-6 col-lg-4">

#### numC

![CS61C-Numc]({{ site.url }}{{ site.baseurl }}/images/projects/cs61cnumc.jpg){: .align-center width="100%" style="max-width:400px"}

For this project, I used C and AVX instruction set to implement a matrix library that can perform matrix multiplication, matrix addition, and matrix transpose. The library is optimized for cache and vectorization.

</div>

<div class="col-sm-12 col-md-6 col-lg-4">
#### Gitlet

![Gitlet]({{ site.url }}{{ site.baseurl }}/images/projects/cs61b-gitlet.png){: .align-center width="100%" style="max-width:400px"}

For this project, I implemented a version control system using Java called Gitlet. Gitlet is a local version control system that mimics the basic features of Git. 

The features implemented are:

1. Stage/Unstage files for commit
2. Commit files
3. Reset to a previous commit
4. Automatically merge branches, and when there is a conflict, the user can manually resolve the conflict

</div>


</div>
