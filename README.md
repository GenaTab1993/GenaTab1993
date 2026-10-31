# Hi, I'm Genady Tabachnik 👋

I am an **Electro-Optics Integration and Test Engineer** with a B.Sc. in Physics and Mathematics. I specialize in hardware automation, optical system alignment, and laboratory validation testing.

---

## Technical Skills

*   **Automation & Instrumentation:** Multi-threading script development, hardware device synchronization, safety loop integration, SCPI Protocol, PyVISA, GPIB, LAN, RS-232.
*   **Data Analysis:** Pandas DataFrames, NumPy, SciPy (curve fitting and statistical error estimation), Matplotlib visualization.
*   **Design & Simulation:** Ansys Zemax OpticStudio (Sequential Mode, lens optimization, OPD fans), LTspice (analog circuit simulation and transient analysis).
*   **Lab Operations:** Cleanroom and ESD-sensitive environments, precision mechanical alignment, Acceptance Test Procedures (ATP), and hardware failure analysis.

---

## Key Projects

### 🔗 [Multi-Instrument Automated LIV Test Executive](https://github.com/GenaTab1993/Optical-Automation-LIV-Data-Engine)
*Automated sweep infrastructure, data analytics pipeline, and hardware design files.*

*   **Multi-Threaded Control:** Built a concurrent architecture using Python's `threading.Event` to coordinate a Keithley SMU and a Keysight Optical Power Meter simultaneously, avoiding race conditions on the instrumentation bus.
*   **Asynchronous Safety Loop:** Integrated a live background thread to monitor sensor temperatures at ~6.6Hz, triggering a fast shutdown (`OUTP OFF`) if the system exceeds a hard 45°C safety limit.
*   **Data Post-Processing:** Developed a pipeline using **Pandas** for structured data cleanup and **SciPy** (`curve_fit`) to calculate laser threshold current and slope efficiency, drawing the final LIV curves alongside a residuals matrix.
  
### 🔗 [Quantum Metrology Engine: Time-Variant HW Verification Framework](https://github.com/GenaTab1993/Quantum_Metrology_Engine)
*Automated electro-optical validation suite coupling deep learning architectures with quantum physics formalisms.*
* **Physics-Driven Deep Learning:** Engineered a multi-layer neural network (`PyTorch`) to model continuous Modulation Transfer Function (MTF) parameters and signal integrity tracks for industrial cameras.
* **Schrödinger Implementation Mode:** Developed a real-time data streaming pipeline to process transient high-frequency waveforms (operating at $50\text{Hz}$) by mapping incoming parameters as dynamically evolving quantum state vectors $|\psi(t)\rangle$.
* **Heisenberg Implementation Mode:** Implemented a continuous online calibration tracking loop to compensate for physical laboratory thermal drift over time, injecting stochastic perturbations directly into the active operator weight matrices $\mathbf{W_1}(t)$ and $\mathbf{W_2}(t)$.

### 🔗 [Quantum Metrology Engine: Open Systems Noise Dynamics Simulator](https://github.com/GenaTab1993/quantum-metrology-open-systems)

*An independent Python implementation of a quantum metrology simulation framework analyzing multi-particle registers under non-unitary environmental coupling.*

- **Generalized Mixed-State QFI Engine:** Developed a spectral Lyapunov solver utilizing the Symmetric Logarithmic Derivative (SLD) representation to accurately calculate parameter estimation sensitivity bounds across discrete clock cycles.
- **Authoritative Physical Tracking Loop:** Engineered a rigorous simulation pipeline tracking explicit density matrix parameter derivatives ($\partial_\theta\rho$) under independent amplitude damping Kraus channels (energy relaxation).
- **Formal Verification Baseline:** Implemented automated numerical checks verifying ideal Schrödinger-Heisenberg representation invariance down to machine precision ($10^{-15}$) alongside continuous Kraus-adjoint map trace duality validation.

> ⚠️ **Note on Development Status:** This repository represents an ongoing, active research framework. The computational modules, numerical experiments, and theoretical appendix benchmarks are not finalized and are subject to continuous optimization and structural adjustments in future versions.


### 🔗 [Camelot Electro-Optical Co-Simulation & Hardware Validation Engine](https://github.com/GenaTab1993/Camelot_Electro_Optical_Cosim)
*Automated co-simulation environment linking discrete transient electrical circuits with dynamic lens diffraction modulation profiles.*
* **Transient Circuit Actuation:** Modeled a low-side N-Channel MOSFET switching stage in Python (synchronized with LTspice telemetry data) operating at 50Hz with a rigid 10ms ON-pulse to capture active rail clamping and loop impedance variations.
* **Diffraction Resolution Evaluation:** Integrated automated extraction of polychromatic FFT MTF profiles up to the physical 144.92 cycles/mm Nyquist cutoff frequency bounded by a 3.45μm pixel pitch CMOS sensor.
* **Parametric Spec Verification:** Automated cross-validation tracking at the core 45.0 lp/mm inspection node, evaluating measured contrast scores against strict Acceptance Test Procedure (ATP) spec-limit compliance baselines (+40% minimum contrast).

### 🔗 [Theoretical Research & Visual Modeling of the Higgs Mechanism](https://github.com/GenaTab1993/Higgs-Mechanism-Particle-Physics)
*Final Course Project - Elementary Particles Course, Department of Physics and Mathematics, University of Haifa, 2021.*

- **Theoretical Literature Review:** Conducted a comprehensive review of electroweak symmetry breaking, local gauge invariants, and non-abelian Yang-Mills field theories based on standard particle physics bibliography.
- **Mathematical Physics Visualization:** Developed custom Python scripts using **NumPy** and **Matplotlib** to mathematically render and plot scalar field configurations, including the unstable local maximum and degenerate vacuum states (Mexican Hat Potential).
- **Phenomenological Illustrations:** Generated structural vector graphics to visually demonstrate spontaneous symmetry breaking concepts, phase transitions, and Goldstone boson elimination modes within the standard model framework.


---

## Engineering Portfolio
For my detailed cross-disciplinary hardware reports, design verifications, and complete laboratory logs across Electrical, Optical, and Automation domains:
🔗 **[Read My Full Engineering Portfolio (Google Docs)](https://docs.google.com/document/d/1Tb6pgupiTu2QQavw6dolYQGQl6Y3FALmsouG02qJByU/edit?usp=drive_link)**


---

## Contact & Logistics

- **Location:** Central District, Israel
- **Professional Profiles:** www.linkedin.com/in/genady-tabachnik | Email: genatab22@gmail.com
- **Note to Recruiters:** I am currently working full-time lab shifts. To maintain confidentiality, **please initiate first contact via LinkedIn InMail, Email, or WhatsApp message only.** Phone calls can be scheduled for after-work hours (from 18:00 onwards) or Fridays. Thank you!

