# Project 2: Quantum for Portfolio Optimization

**Team Information:**  
• **Team Member 1:**  
Full Name: Mackenson Polché  
Wiser Program Enrollment ID: gst-RsShCt7jVtKW0Du  

• **Team Member 2:**  
Full Name: Hein Zay Yar Oo  
Wiser Program Enrollment ID: gst-h5wj9ujY8HtWbMU  

**Exploration of the Project Solution.**  
This repository contains two principal approaches for quantum portfolio optimization: **Classical_Approach** with quantum-inspired methods and **Quantum_Approach** with full quantum implementations. The Classical Approach explores quantum-inspired optimization techniques while the Quantum Approach implements full quantum algorithms using VQE and QAOA on quantum simulators.  

---

### **1) Classical_Approach Folder - Quantum-Inspired Methods**  
This folder contains classical implementations with quantum-inspired optimization techniques, serving as benchmarks for our quantum solutions.

**1.Task1.ipynb**  
This notebook implements the initial portfolio optimization setup, including data preprocessing and classical baseline development.

**5.Task5.ipynb**  
This notebook focuses on advanced constraint handling and penalty methods for portfolio optimization, comparing classical optimization techniques vs Quantum algorithm.

**bond_data.json**  
Dataset containing bond information including sectors, prices, durations, yields, and risk metrics used in portfolio construction.

**quantum_penalized_qaoa.lp**  
Optimization model file for QAOA-inspired portfolio optimization with penalty constraints.

**quantum_penalized_vqe.lp**  
Optimization model file for VQE-inspired portfolio optimization with penalty constraints.

**qaoa_mask_20250810-154943.json**  
Saved parameter mask for QAOA-inspired optimization runs (date-timestamped).

**vqe_mask_20250810-154943.json**  
Saved parameter mask for VQE-inspired optimization runs (date-timestamped).

---

### **2) Quantum_Approach Folder - Quantum Algorithms**  
This folder contains full quantum implementations using VQE and QAOA for portfolio optimization.

**VQE_Optimization.ipynb**  
Main notebook implementing the Variational Quantum Eigensolver (VQE) approach for portfolio optimization. Includes quantum circuit construction, parameter optimization, and result analysis.

**QAOA_Optimization.ipynb**  
Main notebook implementing the Quantum Approximate Optimization Algorithm (QAOA) approach. Contains problem mapping to quantum circuits, layer implementation, and result evaluation.

---

**Additional Files:**  
**Summary_Project.docx**  
Comprehensive project report detailing methodology, comparative analysis of approaches, and quantitative results.

**Presentation_Deck.pptx**  
Final presentation summarizing key findings, approach comparisons, and visual results.  
 [Video Explanation of Presentation Deck](https://drive.google.com/file/d/1XUs6XI8d-iXvxbAhGx-bG_7zMuyher1S/view?usp=sharing)

**README.md**  
This file providing an overview of the repository structure and contents.

---

**Implementation Note:**  
Our quantum implementations leverage both simulators and actual quantum hardware where accessible. For hardware runs, we employed error mitigation techniques and optimized circuit compilation to address noise limitations. Future work will focus on scaling to larger portfolios and enhancing noise resilience.

We appreciate you taking the time to explore this project. Developing both classical-quantum hybrid approaches and full quantum solutions for portfolio optimization has required careful design and iterative validation. We hope our notebooks, data files, and results make our approaches clear and reproducible.

To the Review Committee of the WISER Quantum Program 2025: Thank you for your consideration and evaluation of our work. We believe this project demonstrates practical applications of quantum computing in finance and provides a foundation for more complex financial optimization problems. We welcome feedback on our quantum-classical integration strategies, constraint formulation, and implementation approaches. Your insights will guide our continued development in this domain.
