# SPaMD

![logo4](https://user-images.githubusercontent.com/83065456/180380303-b4c5a121-9582-446e-b943-99f8b6da4648.gif)

Scalable Parallel Materials/Molecular Design/Dynamics Studio 

Updated in Ver.1.5: 
Simulation: Overhaul simulation UI for VASP. Add several implementations for VASP/Basiseries module, e.g. Structure Optimization, Single Point, Molecular Dynamics, Basic Band Structure, Fat Band Structure, 3d Band Structure, Density of States, Fermi Surface, Valence Charge Density, Partial Charge Density, Electron Local Function, Local Potential, Wave Function in real space. Add port to select default server for simulation module. Add auto download routine and preview routine for simulation result. 
Analysis: Add the on-site visualization for AADIS module: DVA, STA, SVA, IDA, NYE and NTA. Improve analysis speed and memory usage for wave function in real space module in VASPA. Add new tools for visualization: Plot Curves of Line+Symbol, Scatter+Colormap, Bubble+Colormap, Vector+Colormap. Enable adding lines to plot curves from data file in CSV format.

Updated in Ver.1.4: 
Simulation:
Add several high-throughput implementations for Simulation module, e.g. ABADE, ACOHP.
Analysis:
Add new module for VASP data analyzer: fat band structure, 3D band structure and fermi surface.
Add new module for VASP volumetric data analyzer: Wave function in real space.
Visualization:
Add new module for atomic visualization mode: polyhedral, plane, vector.
Overhaul bond definition, enable complex cutoff between atoms.
Overhaul colorbar selection, enable custom definition of colorbar.
Add new module for Brillouin zone visualization, K-path definition, and fermi surface visualization.
Add new module: colorfill surface for 3D data visualization.

Updated in Ver.1.3: Add several high-throughput implementations for Simulation module, e.g. AELAS, ADAIS, ASURF, AEDOS, ABAND, APHON; Add the analysis modules for VASP results, e.g. VASPDV for density of state (DOS) and band structure, VASPVV for charge density difference (CDD) and electron localization function (ELF); fix the bugs for modelling, Simulation and visualization modules. 

Updated in Ver.1.2: Add Surfkit for Modelling module; Add support for GUI to VASP for automatically including more functionals by other developer or users; fix the bugs for Simulation and visualization module. 

Updated in Ver.1.1: Add Cryskit for Modelling module; fix the bugs for Simulation module, support submit task to current terminal. 

SPaMD Studio includes the following features: 
1) a user-friendly GUI for operation and visualization; 
2) high-throughput first principles calculation module via VASP and VASPMATE, e.g. ABADE, ACOHP, AEDOS, ABAND, APHON, AELAS, ADAIS, ASURF, AVCDD, AWFUN etc.
3) high-resolution visualization for fat band structure, 3D band structure, fermi surface, wave function in real space, etc. And atomic visualization mode via polyhedral, plane, vector. 
4) a robust rendering system designed for several million atoms or more, supporting color-coding, camera control, atom pickup, and anti-aliasing rendering; 
5) a modular modeling system that supports the direct construction of nanoparticles, nanowires, nanosheets, polycrystals with different axial ratios, bilayers and multilayers, as well as dislocation and crack insertion; 
6) a custom modeling system called atomkit, which provides geometrical selection (e.g., slice, cubic, sphere, prism, polyhedron), multilevel region adjustment (e.g., move, deform, rotate) with boolean selection (e.g., and, or, not), and basic operations (e.g., add, delete, random displace, duplicate, deform); 
7) workflow templates that can be defined with preconfigured operations for quick access and used to perform the same operations with the same settings in different simulations; 
8) adaptive real-time analysis that supports the topological methods of CNA, BAA, CSP, CNP, OIM, and LCO that were previously implemented in our AACSD code; 
9) a post-analysis system that is packaged for vector and tensor analysis methods, i.e., DVA, STA, DDA, SVA, IDA, and NTA, which were recently released in our AADIS code; 
10) an automatic task management system for high-throughput simulation, e.g., dynamic tension/compression, shock loading, and fracture toughness calculation via the internal SPaMD Simulator or other external simulators e.g., LAMMPS;  
11) an internal robust SPaMD simulator that supports molecular dynamics simulations through various ensembles such as NVE, NVT, and NPT, as well as molecular statics methods via CG and FIRE.

Online registration form can be found via Google sites:
https://sites.google.com/site/zrfbuaa/softwares/registration-form

Pasted below is Baidu share link to download SPaMD Studio:
https://pan.baidu.com/s/1O5OKTI-h_pLGxo8n35I-cQ access code：0ejx

Some tutorials can refer to WeChat official account: SPaMD Studio, or Alternatively, scan the following QR code to get access:
![wechat](https://github.com/zrfcms/SPaMD/assets/83065456/32ee3de3-6eec-4b5e-b39d-a35dcce45143)
