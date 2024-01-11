# Awesome Operations Research [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

> Archived to avoid any bias, a good alternative is: https://github.com/ebrahimpichka/awesome-optimization

## Contents

- [Software](#software)
  - [Free](#free)
  - [Commercial](#commercial)
- [Modeling Languages and Interfaces](#modeling-languages-and-interfaces)
- [Courses](#courses)
- [Websites](#websites)
- [Conferences](#conferences)
- [Papers](#papers)
- [Books](#books)
- [People](#people)

## Software

### Free

- [OR-Tools](https://developers.google.com/optimization) - Open source suite by Google.
- [OptaPlanner](https://www.optaplanner.org/) - Open source CP Solver.
- [COIN-OR](https://www.coin-or.org/) - Open source suite.
- [HiGHS](https://www.maths.ed.ac.uk/hall/HiGHS/) - Open source serial and parallel solvers for LP, MIP and QP.

### Commercial

| Solver name                                                              | Company               | Supported problem types                                      |
|--------------------------------------------------------------------------|-----------------------|--------------------------------------------------------------|
| [CPLEX](https://www.ibm.com/analytics/cplex-optimizer)                   | IBM                   | (MI)LP, (non)convex (MI)QP, (MI)SOCP                         |
| [Gurobi](https://www.gurobi.com/)                                        | Gurobi                | (MI)LP, (non)convex (MI)QP, (non)convex (MI)QCP              |
| [FICO Xpress](https://www.fico.com/en/products/fico-xpress-optimization) | FICO                  | (MI)LP, (MI)SOCP                                             |
| [LocalSolver](https://www.localsolver.com/)                              | LocalSolver           | (MI)LP, (non)convex (MI)QP, (non)convex (MI)QCP, (MI)NLP, CP |
| [SCIP](https://www.scipopt.org/)                                         | Zuse Institute Berlin | (MI)LP, (MI)NLP                                              |
| [Knitro](https://www.artelys.com/solvers/knitro/)                        | Artelys               | (MI)LP, (MI)SOCP, (MI)NLP                                    |
| [Mosek](https://www.mosek.com/)                                          | Mosek                 | (MI)LP, (MI)QP, (MI)SOCP, SDP, EXP, POW, GEOMEAN             |
| [Concorde](http://www.math.uwaterloo.ca/tsp/concorde.html)               | UWaterloo             | TSP                                                          |

Meaning of the acronyms:

- LP: linear programming
- QP: quadratic programming
- SOCP: second-order cone programming
- QCP: quadratically-constrained programming
- NLP: nonlinear programming
- CP: constraint programming
- SDP: semi-definite programming
- EXP: exponential code programming
- POW: power code programming
- GEOMEAN: geometrical mean cone programming
- TSP: travelling salesperson problem

## Modeling Languages and Interfaces

- [MiniZinc](https://www.minizinc.org/) - Constraint modeling language.
- [GAMS](https://www.gams.com/) - High-level modeling system, no constraint programming.
- [AMPL](https://www.ampl.com/) - Algebraic modeling language, both linear/integer and constraint programming.
- [JuMP](https://jump.dev/) - Open source modeling language for Julia, mostly linear/integer programming.
- [Pyomo](http://www.pyomo.org/) - Open source modeling library for Python, only linear/integer programming.
- [PuLP](https://coin-or.github.io/pulp/) - Open source modeling library for Python, only linear/integer programming.

## Courses

- [Discrete Optimization](https://www.coursera.org/learn/discrete-optimization) - Course offered by The University of Melbourne.
- [Basic Modeling for Discrete Optimization](https://www.coursera.org/learn/basic-modeling) - Basic modeling course taught using MiniZinc.
- [Advanced Modeling for Discrete Optimization](https://www.coursera.org/learn/advanced-modeling) - Advanced modeling course taught using MiniZinc.

## Websites

- [Amazon science](https://www.amazon.science/research-areas/operations-research-and-optimization) - Papers and blog posts by Amazon.
- [StackExchange](https://or.stackexchange.com/) - Stack Exchange site for Operations Research.
- [Subreddit](https://www.reddit.com/r/OperationsResearch/) - r/OperationsResearch subreddit.

## Conferences

- [CPAIOR](https://cpaior.org/) - Integration of Constraint Programming, Artificial Intelligence, and Operations Research.
- [CP Conference](https://www.a4cp.org/events/cp-conference-series) - Principles and Practice of Constraint Programming.
- [INFORMS](https://www.informs.org/) - Institute for Operations Research and the Management Sciences.

## Papers

## Books

### Introductory

- [Operations Research: An Introduction](https://www.pearson.com/us/higher-education/program/Taha-Operations-Research-An-Introduction-10th-Edition/PGM334070.html) - Introductory book by Hamdy A. Taha.
- [Operations Research: Applications and Algorithms](https://www.amazon.com/Operations-Research-Applications-Algorithms-InfoTrac/dp/0534380581) - Introductory book by Wayne L. Winston.
- [Introduction To Operations Research](https://www.amazon.com/Lieberman-Nag-Basu-Hillier/dp/9339221850) - General reference by Hillier, Lieberman, Nag, Basu.
- [Applied Mathematical Programming](http://web.mit.edu/15.053/www/AppliedMathematicalProgramming.pdf) - Reference book by Bradley, Hax, and Magnanti, used at MIT.
- [Linear Programming: Foundations and Extensions](https://www.amazon.com/dp/303039414X/) - Introductory book with a focus on the simplex algorithm by Robert J. Vanderbei.
- [Introduction to Mathematical Optimization](https://www.amazon.com/dp/1692792024/) - Introductory book with a focus on integer programming by Matteo Fischetti.
- [Combinatorial Optimization](https://www.amazon.com/dp/3540443894/) - Introductory book on combinatorial optimization with a strong mathematical background by Alexander Schrijver.
- [Model Building in Mathematical Programming](https://www.wiley.com/en-ie/Model+Building+in+Mathematical+Programming,+5th+Edition-p-9781118443330) - Introductory modeling book by H. Paul Williams.
- [Network Flow Algorithms](https://www.amazon.com/Network-Flow-Algorithms-David-Williamson/dp/1107185890) - Introductory book on flow algorithms, by David P. Williamson.
- [Handbook of Constraint Programming](https://www.amazon.com/dp/0444527265) - Introductory CP book by F. Rossi, Peter van Beek and Toby Walsh.
- [Algorithms Illuminated: Algorithms for NP-Hard Problems](https://www.amazon.com/Algorithms-Illuminated-Part-NP-Hard-Problems/dp/0999282964) - Intuitive view on combinatorial optimisation problems as part of an algorithms course (introductory for operational research, advanced for algorithms), by Tim Roughgarden.

### Advanced

- [Introduction to Linear Optimization](https://www.amazon.com/dp/1886529191) - Second course on LP by Dimitris Bertsimas, John N. Tsitsiklis, John Tsitsiklis.
- [Integer programming](https://link.springer.com/book/10.1007/978-3-319-11008-0) - Complete book on theory of integer programming, up to data, Michele Conforti, Gérard Cornuéjols, Giacomo Zambelli.
- [Linear Programming](https://www.amazon.com/dp/1429280514/) - Complete covering of LP, focus on notations by Václav Chvátal.
- [Combinatorial Optimization: Algorithms and Complexity](https://www.amazon.com/dp/0486402584) - Focus on complexity, slightly outdated book, by Christos H. Papadimitriou, Kenneth Steiglitz.
- [Integer Programming](https://www.wiley.com/en-us/Integer+Programming%2C+2nd+Edition-p-9781119606536) - Very terse but complete book, by Laurence Wolsey.
- [50 Years of Integer Programming 1958-2008](https://link.springer.com/book/10.1007/978-3-540-68279-0) - Historical review of key results.
- [Introduction to Optimization and Hadamard Semidifferential Calculus](https://www.amazon.com/Introduction-Optimization-Hadamard-Semidifferential-Calculus/dp/1611975956) - Overview book of the field of semidifferentiable optimisation by Michel C. Delfour.

### Reference

- [Theory of Linear and Integer Programming](https://www.amazon.com/dp/0471908541/) - Very advanced book, mostly useful as a reference for key results by Alexander Schrijver.

## People

- [Håkan Kjellerstrand](http://hakank.org/) - Independent Researcher, focused on CP.
- [Erwin Kalvelagen](https://yetanothermathprogrammingconsultant.blogspot.com/) - Math Programming Consultant.
- [Paul A. Rubin](https://orinanobworld.blogspot.com/) - Professor Emeritus of Management Science.
