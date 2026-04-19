<h1 align="center">Hi, I'm Ali 👋</h1>

<p align="center">
  <em>MSc in Physics &amp; Mathematics · University of Granada, Spain</em>
</p>

<p align="center">
  <a href="mailto:alisalemstd@gmail.com">
    <img src="https://img.shields.io/badge/email-alisalemstd%40gmail.com-blue?style=flat-square&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/Alisama20">
    <img src="https://img.shields.io/badge/GitHub-Alisama20-181717?style=flat-square&logo=github"/>
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/alisama">
    <img src="https://img.shields.io/badge/LinkedIn-alisama-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/>
  </a>
</p>

---

## About me

I am a physics and mathematics student with a strong interest in **computational methods for physical systems**. My main research areas are:

🔵 &nbsp;**Computational Electromagnetics** — integral equation methods, scattering, wave propagation  
🟢 &nbsp;**Monte Carlo Methods** — stochastic simulation, diffusion MC, particle-in-cell  
🔴 &nbsp;**Numerical Methods in general** — spectral methods, finite differences, integrators, FFT

I enjoy working at the intersection of mathematical rigour and physical intuition, building solvers from scratch and comparing them with theoretical predictions.

---

## 🛠 Tools

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Numba-00A3E0?style=flat-square"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square"/>
  <img src="https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
</p>

---

## 📂 Projects

<!-- ═══════════════════════════════════════════════════════════════════ -->
### ⚡ Collisionless Plasma · Vlasov–Maxwell

<table>
<tr>
<td width="340">

**[Collisionless-Plasma-Vlasov-Maxwell](https://github.com/Alisama20/Collisionless-Plasma-Vlasov-Maxwell)**

Semi-Lagrangian schemes and Particle-in-Cell (PIC) Monte Carlo for the 1D Vlasov–Maxwell system. Simulates Weibel (electromagnetic) and two-stream (electrostatic) plasma instabilities. Implements Strang splitting with cubic Catmull–Rom interpolation and FFT-based Poisson solver.

</td>
<td width="340" align="center">
<img src="https://raw.githubusercontent.com/Alisama20/Collisionless-Plasma-Vlasov-Maxwell/master/figures/twosteaminestability.png" width="320"/>
<br><sub><em>Two-stream instability: exponential growth of the electric field and electrostatic energy</em></sub>
</td>
</tr>
</table>

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
### 🌐 Computational Electromagnetics · Method of Moments

<table>
<tr>
<td width="340" align="center">
<img src="https://raw.githubusercontent.com/Alisama20/MoM-electromagnetic-scattering/master/figures/RCS2DMFIE.png" width="320"/>
<br><sub><em>Radar cross section of a 2D PEC cylinder — MFIE vs analytical solution</em></sub>
</td>
<td width="340">

**[MoM-electromagnetic-scattering](https://github.com/Alisama20/MoM-electromagnetic-scattering)**

Method of Moments implementation of EFIE and MFIE for electromagnetic scattering by PEC bodies. Solves 2D cylinder (pulse and triangular basis) and 3D sphere (RWG basis functions). Validated against analytical Mie series.

</td>
</tr>
</table>

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
### 🎲 Quantum Monte Carlo · Harmonic Bosons

<table>
<tr>
<td width="340">

**[Diffusion-Monte-Carlo-for-harmonic-bosons](https://github.com/Alisama20/Diffusion-Monte-Carlo-for-harmonic-bosons)**

Diffusion Monte Carlo (DMC) simulation of $N$ interacting bosons in a 1D harmonic trap. Implements both pure DMC and importance-sampling DMC with a Jastrow trial wave function. Demonstrates $1/N$ convergence of the ground-state energy.

</td>
<td width="340" align="center">
<img src="https://raw.githubusercontent.com/Alisama20/Diffusion-Monte-Carlo-for-harmonic-bosons/master/figures/E0DMCISN100.png" width="320"/>
<br><sub><em>Ground-state energy distribution for N=100 bosons — importance-sampling DMC</em></sub>
</td>
</tr>
</table>

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
### 🌊 Quantum Dynamics · Time-Dependent Schrödinger Equation

<table>
<tr>
<td width="340" align="center">
<img src="https://raw.githubusercontent.com/Alisama20/Crank-Nicolson-solution-of-the-time-dependent-Schrodinger-equation/master/figures/wavepacket_high.png" width="320"/>
<br><sub><em>Gaussian wave packet scattering off a rectangular barrier</em></sub>
</td>
<td width="340">

**[Crank-Nicolson-TDSE](https://github.com/Alisama20/Crank-Nicolson-solution-of-the-time-dependent-Schrodinger-equation)**

Cayley (Crank–Nicolson) integrator for the 1D time-dependent Schrödinger equation. Exact norm conservation, transmission coefficient $T(\lambda)$ vs analytical formula, and Monte Carlo quantum measurement simulation.

</td>
</tr>
</table>

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
### 📐 Spectral Methods · Helmholtz Equation

<table>
<tr>
<td width="340">

**[Chebyshev-Spectral-Galerkin-Helmholtz](https://github.com/Alisama20/Chebyshev-Spectral-Galerkin-Method-for-the-Helmholtz-Equation-Theory-and-Implementation)**

Chebyshev spectral–Galerkin discretisation of the 2D Helmholtz equation. Includes full theoretical derivation of the weak formulation, construction of basis functions satisfying Dirichlet BCs, Kronecker-product matrix assembly, and exponential convergence study.

</td>
<td width="340" align="center">
<img src="https://raw.githubusercontent.com/Alisama20/Chebyshev-Spectral-Galerkin-Method-for-the-Helmholtz-Equation-Theory-and-Implementation/master/figures/convergence.png" width="320"/>
<br><sub><em>Exponential (spectral) convergence of the Chebyshev–Galerkin method</em></sub>
</td>
</tr>
</table>

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
### 🌌 N-body Dynamics · Molecular &amp; Planetary

<table>
<tr>
<td width="340" align="center">
<img src="https://raw.githubusercontent.com/Alisama20/Verlet-algorithm-applied-to-molecular-and-planetary-dynamics/master/figures/formation_disk.png" width="320"/>
<br><sub><em>Protoplanetary disk formation via inelastic collisions — N-body simulation</em></sub>
</td>
<td width="340">

**[Verlet-algorithm-applied-to-molecular-and-planetary-dynamics](https://github.com/Alisama20/Verlet-algorithm-applied-to-molecular-and-planetary-dynamics)**

Velocity-Verlet N-body integrator (Numba-accelerated) for the Solar System, planet-formation via inelastic collisions, and 2D Lennard-Jones molecular dynamics. Tracks energy conservation, radial distribution function, and temperature equilibration.

</td>
</tr>
</table>

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
### 🔬 Quantum Transport · Nanoelectronics

<table>
<tr>
<td width="340">

**[Quantum-transport-nanoelectronics](https://github.com/Alisama20/Quantum-transport-nanoelectronics)**

Quantum transport simulation in 1D nanostructures: particle-in-a-box, double-well potential, and ballistic MOSFET I–V characteristics. Solves the Schrödinger equation self-consistently with quantum confinement effects and computes conductance vs gate voltage.

</td>
<td width="340" align="center">
<img src="https://raw.githubusercontent.com/Alisama20/Quantum-transport-nanoelectronics/master/figures/mosfet_iv_family.png" width="320"/>
<br><sub><em>MOSFET I–V family of curves with quantum confinement</em></sub>
</td>
</tr>
</table>

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
### 🪐 Celestial Mechanics · Restricted Three-Body Problem

<table>
<tr>
<td width="340" align="center">
<img src="https://raw.githubusercontent.com/Alisama20/Earth-Moon-Spacecraft-or-Meteorite-restricted-three-body-problem/master/figures/rocket_trajectory_escape.png" width="320"/>
<br><sub><em>Spacecraft escape trajectory in the Earth–Moon rotating frame</em></sub>
</td>
<td width="340">

**[Earth-Moon-Spacecraft-restricted-three-body](https://github.com/Alisama20/Earth-Moon-Spacecraft-or-Meteorite-restricted-three-body-problem)**

Numerical integration of the circular restricted three-body problem (CR3BP) in the Earth–Moon system. Explores Lagrange points, Jacobi integral conservation, spacecraft transfer orbits, and chaotic meteorite trajectories.

</td>
</tr>
</table>

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
### 📈 Critical Phenomena &amp; Cooperative Systems

<table>
<tr>
<td width="340">

**[Critical-and-Cooperative-Phenomena-Simulations](https://github.com/Alisama20/Critical-and-Cooperative-Phenomena-Simulations)**

Monte Carlo simulations of critical phenomena: KPZ universality class, scaling collapse, and wetting dynamics. Extracts critical exponents via finite-size scaling and validates against theoretical predictions of the KPZ universality class.

</td>
<td width="340" align="center">
<img src="https://raw.githubusercontent.com/Alisama20/Critical-and-Cooperative-Phenomena-Simulations/master/figures/varianzasRDSR.png" width="320"/>
<br><sub><em>Interface width variance vs time — KPZ universality class (RDSR model)</em></sub>
</td>
</tr>
</table>

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
### 🎲 FFT &amp; Quantum Physics

<table>
<tr>
<td width="340" align="center">
<img src="https://raw.githubusercontent.com/Alisama20/FFT-and-quantum-physics/master/figures/harmonic_oscillator.png" width="320"/>
<br><sub><em>Quantum harmonic oscillator ground state via imaginary-time FFT propagation</em></sub>
</td>
<td width="340">

**[FFT-and-quantum-physics](https://github.com/Alisama20/FFT-and-quantum-physics)**

Self-contained recursive and iterative FFT implementations validated against analytical DFTs and NumPy. Applied to the quantum harmonic oscillator via FFT-based split-operator imaginary-time propagation. Includes performance benchmarks.

</td>
</tr>
</table>

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
### 🧬 Stochastic Evolutionary Game Theory

<table>
<tr>
<td width="340">

**[Stochastic-Evolutionary-Game-Theory](https://github.com/Alisama20/Stochastic-Evolutionary-Game-Theory)**

Monte Carlo simulation of evolutionary dynamics in finite populations. Computes fixation probabilities and fixation times for different game-theoretic payoff matrices, comparing stochastic results with analytical predictions from the Moran process.

</td>
<td width="340" align="center">
<img src="https://raw.githubusercontent.com/Alisama20/Stochastic-Evolutionary-Game-Theory/master/figures/fixation_probability.png" width="320"/>
<br><sub><em>Fixation probability vs initial frequency — Monte Carlo vs analytical Moran process</em></sub>
</td>
</tr>
</table>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Alisama20&show_icons=true&theme=default&hide_border=true&count_private=false" height="150"/>
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Alisama20&layout=compact&hide_border=true&theme=default" height="150"/>
</p>

---

<p align="center">
  <sub>University of Granada · Faculty of Sciences · Academic Year 2025/2026</sub>
</p>
