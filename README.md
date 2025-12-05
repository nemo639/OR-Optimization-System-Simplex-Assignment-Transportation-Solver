📘 OR Optimization System – Simplex, Assignment & Transportation Solver

A complete Operations Research–based optimization system built using Python.
This project provides production planning, workforce assignment, and transportation cost minimization using:

Simplex Method (LP)

Hungarian Algorithm (Assignment Problem)

Vogel’s Approximation + UV/MODI (Transportation Problem)

Advanced Sensitivity Analysis for all models

A Tkinter-based GUI for easy interaction

🚀 Project Overview

TechElectro Manufacturing faces three major decision-making challenges:

Optimal Production Quantities under multiple resource constraints

Worker-to-Task Assignment minimizing total assembly time

Distribution Optimization for shipping products from factories to warehouses

This system solves all three problems, displays results through a GUI, and provides detailed sensitivity insights that help managers understand how changes in costs, resources, and structure affect optimal decisions.

🧠 Features
✔ Simplex Method (LP Solver)

Computes optimal production quantities for 10 products

Shows maximum achievable profit

Identifies binding & non-binding constraints

Provides shadow prices, reduced costs, RHS ranges, coefficient ranges

Advanced Sensitivity:

Effect of changing A-matrix coefficients

Adding a new constraint

Adding a new product (new decision variable)

✔ Hungarian Assignment Solver

Assigns 10 workers to 10 tasks

Minimizes total assembly time

Provides:

Opportunity cost analysis

Cost tolerance ranges

Worker efficiency evaluation

✔ Transportation Optimization Solver

Handles 10 factories × 10 warehouses

Computes initial solution using VAM

Improves to optimal using UV/MODI

Shows:

Dual variables (u, v)

Reduced costs

Route efficiency analysis

Supply & demand utilization

✔ Graphical User Interface (GUI)

Built using Tkinter

Three separate tabs:

Simplex Solver

Assignment Solver

Transportation Solver

User-friendly layout for input and output

📸 Screenshots
🧮 Simplex Optimal Solution



🔍 Sensitivity Analysis



👷 Assignment Results



🚚 Transportation Plan



🛠️ How to Run the Project
1. Clone the Repository
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name

2. Install Required Dependencies
pip install numpy
pip install scipy


(Tkinter is included by default in most Python installations.)

3. Run the Application
python or_1.py


The GUI window will open.

📂 Project Structure
├── or_1.py              # Main application with GUI + all solvers
├── README.md            # GitHub documentation
└── assets/              # (Optional) Screenshots for documentation

📘 Algorithms Used
🔹 Simplex Method (HiGHS via SciPy)

Used for maximizing profit under linear constraints.

🔹 Hungarian Algorithm

Used for minimizing total assignment cost.

🔹 VAM + UV/MODI

Used for transportation cost minimization and optimality checking.

🎯 Key Learning Outcomes

Application of OR techniques to real-world business problems

Integration of LP, Assignment, and Transportation models

Implementation of advanced sensitivity analysis

GUI development in Python for decision-support systems

🤝 Contributions

Feel free to fork this repository, submit issues, or create pull requests.

📝 License

This project is released under the MIT License.

⭐ If you like this project, consider starring the repository!
