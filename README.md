**AdDiff1DSolver**
This project implements a 1D Advection-Diffusion solver using the deal.II finite element library. It numerically solves the advection-diffusion equation on a 1D grid using finite element methods, allowing for the analysis of diffusion and advection phenomena.

**Key Features:**
1.1D Grid Setup: A 1D grid is created and refined.
2.Finite Element Space: Linear finite elements (FE_Q<1>) are used for discretization.
3.System Assembly: The system matrix and right-hand side vector are generated.
4.Boundary Conditions: Simple Dirichlet boundary conditions are applied.
5.Solver: The BiCGStab solver is used to solve the linear system.
6.Output: The solution is outputted to the console.
**Setup & Usage:**
1.Dependencies: This project requires the deal.II library.
2.Compilation: Build using CMake, linking with deal.II.
3.Running: Compile and execute to solve the problem and view the output in the console.
**Future Extensions:**
.Add more complex boundary conditions.
.Extend to time-dependent problems.
.Provide visualization outputs using VTK or other formats.

**AdvancedAdDiffSolver2D**
This project implements a 2D Advection-Diffusion solver using the deal.II finite element library. The solver aims to numerically solve the advection-diffusion equation over a 2D unit square grid. It is designed to be flexible and extensible, with a focus on clear, modular code for easy adaptation to different problems.
**Key Features:**
1.2D Grid Setup: The code generates a unit square grid, refined to improve accuracy.
2.Finite Element Space: Linear finite elements (FE_Q<2>) are used for discretizing the problem.
3.System Assembly: The system matrix and right-hand side vector are constructed based on the advection-diffusion equation.
4.Boundary Conditions: Dirichlet boundary conditions are applied to the system.
5.Solver: The BiCGStab solver is used to solve the system of equations iteratively.
6.Output: A basic function is provided to output the computed solution.
**Setup & Usage:**
1.Dependencies: This project requires the deal.II library.
2.Compilation: Use CMake to build the project, linking with deal.II.
3.Running: Simply compile and execute to see the solution in the console.
**Future Improvements:**
.Implementing different boundary conditions.
.Extending the solver to handle time-dependent problems.
.Adding a more sophisticated output mechanism (e.g., VTK for visualization).
