<h1 style="color:#1E90FF;">🌐 Network Function Virtualization (NFV) — SFC Placement & Simulation</h1>

**Master’s Thesis Project (Final Semester)**  
**Contributor:** Sri Sai Rajesh  

---

<h2 style="color:#FF6347;">🌟 About This Project</h2>

During my final semester of my **Master’s in Computer Science**, I developed this **thesis-level project**, which is my **only coding-intensive master’s project**. The focus is on **Network Function Virtualization (NFV)**, specifically **Service Function Chain (SFC) placement** and simulation.  

The objective was to **analyze real network traffic**, generate candidate network paths, and **optimize the placement of Virtual Network Functions (VNFs)** to improve **network efficiency and performance**.

Key contributions include:  

- **Data preprocessing** and *flow aggregation* from packet captures  
- **Designing network topologies** and defining VNFs with CPU and bandwidth constraints  
- **Developing candidate path algorithms** for Service Function Chains (SFCs)  
- **Implementing placement algorithms:**  
  - **Greedy Approach:** Fast, heuristic-based placement to quickly find near-optimal solutions in large networks  
  - **Dynamic Programming (DP) Approach:** Guarantees optimal placement by evaluating multiple combinations efficiently, ideal for constrained resources  
  - **MILP (Mixed-Integer Linear Programming):** Exact optimization for benchmarking  
- **Visualization and analysis** of results to compare different placement strategies  

This project uniquely **bridges theory and practical coding**, demonstrating my ability to work with **real network traffic, advanced optimization algorithms, and large datasets**.

---

<h2 style="color:#32CD32;">🧰 Key Skills & Technologies Used</h2>

- **Programming & Analysis:** Python, Pandas, NumPy  
- **Network Simulation:** NetworkX, Packet capture analysis  
- **Optimization & Algorithms:** *Greedy heuristics*, *Dynamic Programming*, *Mixed-Integer Linear Programming (PuLP)*  
- **Visualization:** Matplotlib, Seaborn  
- **Research Output:** Full thesis report and presentation slides  

---

<h2 style="color:#FFA500;">📂 Repository Structure</h2>

- **RAJESH.ipynb** — Interactive notebook with all code, simulations, and analysis  
- **Rajesh_SFC_Final_Thesis_Report.pdf** — Full thesis report detailing methodology and results  
- **Rajesh_PPT_25-11-2025.pptx** — Presentation slides summarizing research  
- **packets.csv, packets.pcapng** — Sample network packet data used for flow aggregation  

---

<h2 style="color:#1E90FF;">🚀 How to Run</h2>

**1. Clone the repository:**  
```bash
git clone https://github.com/srv9989/Thesis-NFV.git
cd Thesis-NFV
2. Install Python dependencies:

pip install pandas numpy networkx matplotlib seaborn pulp
3. Open the notebook:

jupyter notebook RAJESH.ipynb
4. Run the notebook cells sequentially to reproduce all simulations, flow aggregation, and placement evaluations.
