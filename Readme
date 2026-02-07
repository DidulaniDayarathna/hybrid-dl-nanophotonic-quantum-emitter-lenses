# Hybrid Deep Learning for Design of Nanophotonic Quantum Emitter Lenses

This repository presents the methodology and machine-learning-driven design framework associated with the research work:

***Hybrid Deep Learning for Design of Nanophotonic Quantum Emitter Lenses***.

The project focuses on leveraging **hybrid deep learning architectures** to enable efficient, high-performance inverse design of nanophotonic lenses tailored for enhancing and directing emission from quantum emitters.

---

## Overview

Nanophotonic lenses for quantum emitters play a critical role in improving light extraction efficiency, directionality, and collection into free space or optical systems. Conventional inverse-design techniques—while powerful—often rely on computationally expensive iterative optimization.

This work introduces a **hybrid deep learning approach** that combines physics-based simulations with neural-network models to accelerate the design process while maintaining high optical performance. The framework enables rapid prediction and inverse synthesis of nanophotonic lens geometries optimized for quantum emission control.

---

## Project Objectives

* **Hybrid Model Development**
  Develop and evaluate hybrid deep learning models that combine classical optimization concepts with modern neural networks for nanophotonic lens design.

* **Forward and Inverse Design**
  Learn mappings between nanophotonic lens geometries and optical responses relevant to quantum emitters, including far-field directionality and collection efficiency.

* **Design Acceleration**
  Reduce the computational cost of lens optimization by replacing iterative solvers with fast ML-based surrogates.

* **Performance Validation**
  Validate ML-generated designs against full-wave electromagnetic simulations.

---

## Methodology

### 1. Physics-Based Data Generation

* **Simulation Method**: Finite-Difference Time-Domain (FDTD)

* **Electromagnetic Solver**: Meep

* **Physical System**:

  * Quantum emitter modeled as a dipole source
  * Nanophotonic lens structures designed to shape and collimate emitted radiation

* **Structure Representation**:

  * Discretized 2D or 3D permittivity maps
  * Geometry encoded as fixed-resolution grids suitable for neural network input

---

### 2. Hybrid Deep Learning Framework

* **Forward Models**
  Neural networks trained to predict optical metrics (e.g., far-field intensity, numerical aperture, collection efficiency) from lens geometries.

* **Inverse Models**
  Networks trained to generate lens designs that meet target emission characteristics.

* **Hybrid Strategy**

  * Dimensionality reduction and/or physics-informed constraints
  * Coupling between forward and inverse networks to stabilize training and resolve non-unique solutions

* **Optimization Loop**
  ML-predicted designs are validated and refined using full-wave simulations.

---

## Key Results

* **High-Performance Lens Designs**
  The hybrid deep learning framework successfully generated nanophotonic lenses with strong directionality and enhanced collection efficiency for quantum emitters.

* **Acceleration Over Traditional Methods**
  Design times were reduced by orders of magnitude compared to purely simulation-driven optimization.

* **Robust Generalization**
  Trained models demonstrated the ability to propose effective lens geometries across a range of emitter positions and target emission profiles.

* **Physics Consistency**
  ML-generated designs closely matched full-wave simulation results, confirming physical validity.

---

## Figures and Visualizations

Key figures related to lens geometries, emission profiles, and model performance are provided in the **`figures/`** directory.

### Example Content

* Quantum emitter–lens configurations
* Far-field radiation patterns
* Comparison between ML-designed and simulation-optimized lenses
* Forward and inverse model prediction accuracy

```markdown
figures/
├── lens_geometry_examples.png
├── far_field_patterns.png
├── hybrid_model_architecture.png
├── inverse_design_results.png
```

To embed figures in this README:

```markdown
![Far-field pattern](figures/far_field_patterns.png)
```

---

## Tech Stack

* **Programming Language**: Python
* **Machine Learning**: TensorFlow / Keras, Scikit-learn
* **Electromagnetic Simulation**: Meep (FDTD)
* **Data Processing & Visualization**: NumPy, Pandas, Matplotlib

---

## Code & Data Access

* **Code**: This repository contains the hybrid deep learning models, training pipelines, and evaluation scripts.
* **Simulation Data**: Generated using FDTD and available upon reasonable request.
* **Reuse & Collaboration**: Please contact the author for commercial use or collaborative research opportunities.

---

## Citation

If you use this repository in academic work, please cite the corresponding paper:

```bibtex
@article{HybridDLQuantumEmitter,
  title   = {Hybrid Deep Learning for Design of Nanophotonic Quantum Emitter Lenses},
  author  = {Acharige, Didulani and Johlin, Eric},
  journal = {To be updated},
  year    = {To be updated}
}
```

---

## Contact

**Didulani Acharige**
Department of Mechanical and Materials Engineering
Western University
Email: [dsalwath@uwo.ca](mailto:dsalwath@uwo.ca)
