# Optimization examples in Python (cvxpy), solved and checked

48 classic optimization problems in 7 topics, as Jupyter notebooks: the problem in words, the model with a note on every line, runnable [cvxpy](https://www.cvxpy.org/) code and its real output from open-source solvers (HiGHS, Clarabel, SCIP) or NumPy. Every answer was checked: feasibility of every constraint and a dual or KKT certificate. **New notebooks are added as new examples are solved:** watch or star the repository to hear about them.

Made by [ProvenDecisions](https://proven-decisions.ai/?ref=github), where each example has a step-by-step walkthrough and you can solve your own problem from typed math, LaTeX, a photo or speech.

## Notebooks

### Linear programming

Plans that make the most profit or cost the least, with linear rules. Folder: [`notebooks/01-linear-programming`](notebooks/01-linear-programming)

| # | Example | Run | Walkthrough |
|---:|---|---|---|
| 1 | [Product mix LP: how many of each product maximizes profit](notebooks/01-linear-programming/product-mix.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/01-linear-programming/product-mix.ipynb) | [walkthrough](https://proven-decisions.ai/examples/product-mix?ref=github) |
| 2 | [Diet problem LP: the cheapest diet that meets every nutrient target](notebooks/01-linear-programming/diet-problem.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/01-linear-programming/diet-problem.ipynb) | [walkthrough](https://proven-decisions.ai/examples/diet-problem?ref=github) |
| 3 | [Blending problem: mix ingredients to meet the specs at the least cost](notebooks/01-linear-programming/blending-problem.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/01-linear-programming/blending-problem.ipynb) | [walkthrough](https://proven-decisions.ai/examples/blending-problem?ref=github) |
| 4 | [Production and inventory planning over several periods, as an LP](notebooks/01-linear-programming/production-inventory-planning.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/01-linear-programming/production-inventory-planning.ipynb) | [walkthrough](https://proven-decisions.ai/examples/production-inventory-planning?ref=github) |
| 5 | [Two-stage supply chain LP: factory to warehouses to store at the least cost](notebooks/01-linear-programming/supply-chain-lp.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/01-linear-programming/supply-chain-lp.ipynb) | [walkthrough](https://proven-decisions.ai/examples/supply-chain-lp?ref=github) |

### Duality and shadow prices

The prices that prove an answer optimal, and what one more unit of a resource is worth. Folder: [`notebooks/02-duality-and-sensitivity`](notebooks/02-duality-and-sensitivity)

| # | Example | Run | Walkthrough |
|---:|---|---|---|
| 6 | [Shadow prices: what one more unit of each resource is worth](notebooks/02-duality-and-sensitivity/shadow-prices.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/02-duality-and-sensitivity/shadow-prices.ipynb) | [walkthrough](https://proven-decisions.ai/examples/shadow-prices?ref=github) |
| 7 | [Dual of the diet problem: the nutrient prices behind the cheapest diet](notebooks/02-duality-and-sensitivity/dual-of-the-diet-problem.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/02-duality-and-sensitivity/dual-of-the-diet-problem.ipynb) | [walkthrough](https://proven-decisions.ai/examples/dual-of-the-diet-problem?ref=github) |
| 8 | [Dual of a transportation problem: the prices that prove the plan optimal](notebooks/02-duality-and-sensitivity/dual-of-a-transportation-problem.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/02-duality-and-sensitivity/dual-of-a-transportation-problem.ipynb) | [walkthrough](https://proven-decisions.ai/examples/dual-of-a-transportation-problem?ref=github) |
| 9 | [LP duality with equality constraints: free dual variables explained](notebooks/02-duality-and-sensitivity/lp-dual-with-equality-constraints.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/02-duality-and-sensitivity/lp-dual-with-equality-constraints.ipynb) | [walkthrough](https://proven-decisions.ai/examples/lp-dual-with-equality-constraints?ref=github) |

### Networks, routing and assignment

Shipping, flows, paths, tours and matching workers to jobs. Folder: [`notebooks/03-networks-and-routing`](notebooks/03-networks-and-routing)

| # | Example | Run | Walkthrough |
|---:|---|---|---|
| 10 | [Transportation problem: the cheapest way to ship from plants to stores](notebooks/03-networks-and-routing/transportation-problem.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/03-networks-and-routing/transportation-problem.ipynb) | [walkthrough](https://proven-decisions.ai/examples/transportation-problem?ref=github) |
| 11 | [Assignment problem: one job per worker at the least total cost](notebooks/03-networks-and-routing/assignment-problem.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/03-networks-and-routing/assignment-problem.ipynb) | [walkthrough](https://proven-decisions.ai/examples/assignment-problem?ref=github) |
| 12 | [Minimum-cost network flow: meet every demand at the least shipping cost](notebooks/03-networks-and-routing/minimum-cost-flow.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/03-networks-and-routing/minimum-cost-flow.ipynb) | [walkthrough](https://proven-decisions.ai/examples/minimum-cost-flow?ref=github) |
| 13 | [Maximum flow problem: the most a network can carry, as a linear program](notebooks/03-networks-and-routing/maximum-flow.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/03-networks-and-routing/maximum-flow.ipynb) | [walkthrough](https://proven-decisions.ai/examples/maximum-flow?ref=github) |
| 14 | [Shortest path written as a linear program, step by step](notebooks/03-networks-and-routing/shortest-path-lp.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/03-networks-and-routing/shortest-path-lp.ipynb) | [walkthrough](https://proven-decisions.ai/examples/shortest-path-lp?ref=github) |
| 15 | [Travelling salesman problem: the shortest tour, as an integer program](notebooks/03-networks-and-routing/travelling-salesman-problem.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/03-networks-and-routing/travelling-salesman-problem.ipynb) | [walkthrough](https://proven-decisions.ai/examples/travelling-salesman-problem?ref=github) |

### Integer programming

Yes-or-no and whole-number decisions: what to open, pack, cut or schedule. Folder: [`notebooks/04-integer-programming`](notebooks/04-integer-programming)

| # | Example | Run | Walkthrough |
|---:|---|---|---|
| 16 | [0-1 knapsack problem: the most valuable set of items that fits](notebooks/04-integer-programming/knapsack-problem.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/04-integer-programming/knapsack-problem.ipynb) | [walkthrough](https://proven-decisions.ai/examples/knapsack-problem?ref=github) |
| 17 | [Facility location: which sites to open to serve every customer](notebooks/04-integer-programming/facility-location.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/04-integer-programming/facility-location.ipynb) | [walkthrough](https://proven-decisions.ai/examples/facility-location?ref=github) |
| 18 | [Capacitated facility location: which sites to open when each has a limit](notebooks/04-integer-programming/capacitated-facility-location.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/04-integer-programming/capacitated-facility-location.ipynb) | [walkthrough](https://proven-decisions.ai/examples/capacitated-facility-location?ref=github) |
| 19 | [Set covering problem: the cheapest choice of sites that covers everyone](notebooks/04-integer-programming/set-covering.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/04-integer-programming/set-covering.ipynb) | [walkthrough](https://proven-decisions.ai/examples/set-covering?ref=github) |
| 20 | [Bin packing problem: the fewest bins that hold every item](notebooks/04-integer-programming/bin-packing.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/04-integer-programming/bin-packing.ipynb) | [walkthrough](https://proven-decisions.ai/examples/bin-packing?ref=github) |
| 21 | [Cutting stock problem: the fewest rolls that cover every order](notebooks/04-integer-programming/cutting-stock.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/04-integer-programming/cutting-stock.ipynb) | [walkthrough](https://proven-decisions.ai/examples/cutting-stock?ref=github) |
| 22 | [Graph colouring as an integer program: the fewest colours needed](notebooks/04-integer-programming/graph-coloring.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/04-integer-programming/graph-coloring.ipynb) | [walkthrough](https://proven-decisions.ai/examples/graph-coloring?ref=github) |
| 23 | [Lot sizing with setup costs: when to produce and how much](notebooks/04-integer-programming/lot-sizing.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/04-integer-programming/lot-sizing.ipynb) | [walkthrough](https://proven-decisions.ai/examples/lot-sizing?ref=github) |
| 24 | [Machine scheduling: assign jobs so the last one finishes soonest](notebooks/04-integer-programming/makespan-scheduling.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/04-integer-programming/makespan-scheduling.ipynb) | [walkthrough](https://proven-decisions.ai/examples/makespan-scheduling?ref=github) |
| 25 | [Fixed-charge problem: setup costs in a production plan, with binaries](notebooks/04-integer-programming/fixed-charge-problem.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/04-integer-programming/fixed-charge-problem.ipynb) | [walkthrough](https://proven-decisions.ai/examples/fixed-charge-problem?ref=github) |
| 26 | [Big-M either-or constraints: model 'one of two rules' with a binary](notebooks/04-integer-programming/big-m-either-or-constraint.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/04-integer-programming/big-m-either-or-constraint.ipynb) | [walkthrough](https://proven-decisions.ai/examples/big-m-either-or-constraint?ref=github) |
| 27 | [LP relaxation versus the integer optimum: why rounding is not enough](notebooks/04-integer-programming/lp-relaxation-vs-integer-optimum.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/04-integer-programming/lp-relaxation-vs-integer-optimum.ipynb) | [walkthrough](https://proven-decisions.ai/examples/lp-relaxation-vs-integer-optimum?ref=github) |

### Statistics and machine learning

Model fitting written as optimization: regression, classification and PCA. Folder: [`notebooks/05-statistics-and-machine-learning`](notebooks/05-statistics-and-machine-learning)

| # | Example | Run | Walkthrough |
|---:|---|---|---|
| 28 | [Least squares line fit, written and solved as an optimization problem](notebooks/05-statistics-and-machine-learning/least-squares-line-fit.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/05-statistics-and-machine-learning/least-squares-line-fit.ipynb) | [walkthrough](https://proven-decisions.ai/examples/least-squares-line-fit?ref=github) |
| 29 | [Least absolute deviations regression: a line fit that resists outliers](notebooks/05-statistics-and-machine-learning/least-absolute-deviations.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/05-statistics-and-machine-learning/least-absolute-deviations.ipynb) | [walkthrough](https://proven-decisions.ai/examples/least-absolute-deviations?ref=github) |
| 30 | [Minimax (Chebyshev) line fit: make the worst error as small as possible](notebooks/05-statistics-and-machine-learning/chebyshev-minimax-line-fit.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/05-statistics-and-machine-learning/chebyshev-minimax-line-fit.ipynb) | [walkthrough](https://proven-decisions.ai/examples/chebyshev-minimax-line-fit?ref=github) |
| 31 | [Ridge regression as an optimization problem (L2 penalty)](notebooks/05-statistics-and-machine-learning/ridge-regression.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/05-statistics-and-machine-learning/ridge-regression.ipynb) | [walkthrough](https://proven-decisions.ai/examples/ridge-regression?ref=github) |
| 32 | [Lasso regression as an optimization problem (L1 penalty)](notebooks/05-statistics-and-machine-learning/lasso-regression.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/05-statistics-and-machine-learning/lasso-regression.ipynb) | [walkthrough](https://proven-decisions.ai/examples/lasso-regression?ref=github) |
| 33 | [Logistic regression as convex optimization: maximum likelihood fit](notebooks/05-statistics-and-machine-learning/logistic-regression.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/05-statistics-and-machine-learning/logistic-regression.ipynb) | [walkthrough](https://proven-decisions.ai/examples/logistic-regression?ref=github) |
| 34 | [Soft-margin support vector machine as a quadratic program](notebooks/05-statistics-and-machine-learning/support-vector-machine.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/05-statistics-and-machine-learning/support-vector-machine.ipynb) | [walkthrough](https://proven-decisions.ai/examples/support-vector-machine?ref=github) |
| 35 | [Principal component analysis as an optimization problem](notebooks/05-statistics-and-machine-learning/principal-component-analysis.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/05-statistics-and-machine-learning/principal-component-analysis.ipynb) | [walkthrough](https://proven-decisions.ai/examples/principal-component-analysis?ref=github) |

### Finance and portfolios

Risk and return, bonds and bet sizing. Folder: [`notebooks/06-finance`](notebooks/06-finance)

| # | Example | Run | Walkthrough |
|---:|---|---|---|
| 36 | [Markowitz portfolio: the least risk for a target return (quadratic program)](notebooks/06-finance/markowitz-portfolio.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/06-finance/markowitz-portfolio.ipynb) | [walkthrough](https://proven-decisions.ai/examples/markowitz-portfolio?ref=github) |
| 37 | [Maximum Sharpe ratio portfolio: the best return per unit of risk](notebooks/06-finance/maximum-sharpe-ratio.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/06-finance/maximum-sharpe-ratio.ipynb) | [walkthrough](https://proven-decisions.ai/examples/maximum-sharpe-ratio?ref=github) |
| 38 | [Mean-absolute-deviation portfolio: risk as a linear program](notebooks/06-finance/mean-absolute-deviation-portfolio.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/06-finance/mean-absolute-deviation-portfolio.ipynb) | [walkthrough](https://proven-decisions.ai/examples/mean-absolute-deviation-portfolio?ref=github) |
| 39 | [CVaR portfolio: limit the average worst-case loss with a linear program](notebooks/06-finance/cvar-portfolio.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/06-finance/cvar-portfolio.ipynb) | [walkthrough](https://proven-decisions.ai/examples/cvar-portfolio?ref=github) |
| 40 | [Cash-flow matching: the cheapest bond portfolio that pays every liability](notebooks/06-finance/cash-flow-matching.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/06-finance/cash-flow-matching.ipynb) | [walkthrough](https://proven-decisions.ai/examples/cash-flow-matching?ref=github) |
| 41 | [Kelly criterion: the bet size that grows wealth fastest](notebooks/06-finance/kelly-criterion.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/06-finance/kelly-criterion.ipynb) | [walkthrough](https://proven-decisions.ai/examples/kelly-criterion?ref=github) |

### Geometry, engineering and economics

Circles and locations, can design, ordering, consumer choice, power and the fastest slide. Folder: [`notebooks/07-geometry-engineering-economics`](notebooks/07-geometry-engineering-economics)

| # | Example | Run | Walkthrough |
|---:|---|---|---|
| 42 | [Economic order quantity (EOQ): the order size with the lowest yearly cost](notebooks/07-geometry-engineering-economics/economic-order-quantity.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/07-geometry-engineering-economics/economic-order-quantity.ipynb) | [walkthrough](https://proven-decisions.ai/examples/economic-order-quantity?ref=github) |
| 43 | [Utility maximization: a consumer's best bundle within a budget](notebooks/07-geometry-engineering-economics/consumer-utility-maximization.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/07-geometry-engineering-economics/consumer-utility-maximization.ipynb) | [walkthrough](https://proven-decisions.ai/examples/consumer-utility-maximization?ref=github) |
| 44 | [Tin can design: the radius and height that use the least metal](notebooks/07-geometry-engineering-economics/tin-can-minimum-surface.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/07-geometry-engineering-economics/tin-can-minimum-surface.ipynb) | [walkthrough](https://proven-decisions.ai/examples/tin-can-minimum-surface?ref=github) |
| 45 | [Smallest enclosing circle: the smallest circle that covers every point](notebooks/07-geometry-engineering-economics/smallest-enclosing-circle.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/07-geometry-engineering-economics/smallest-enclosing-circle.ipynb) | [walkthrough](https://proven-decisions.ai/examples/smallest-enclosing-circle?ref=github) |
| 46 | [Largest circle inside a polygon (Chebyshev center), as a linear program](notebooks/07-geometry-engineering-economics/largest-inscribed-circle.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/07-geometry-engineering-economics/largest-inscribed-circle.ipynb) | [walkthrough](https://proven-decisions.ai/examples/largest-inscribed-circle?ref=github) |
| 47 | [Fermat-Weber point: where a warehouse minimizes total distance](notebooks/07-geometry-engineering-economics/fermat-weber-warehouse-location.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/07-geometry-engineering-economics/fermat-weber-warehouse-location.ipynb) | [walkthrough](https://proven-decisions.ai/examples/fermat-weber-warehouse-location?ref=github) |
| 48 | [Water-filling: share power across channels to maximize capacity](notebooks/07-geometry-engineering-economics/water-filling.ipynb) | [Open in Colab](https://colab.research.google.com/github/ProvenDecisions/optimization-examples/blob/main/notebooks/07-geometry-engineering-economics/water-filling.ipynb) | [walkthrough](https://proven-decisions.ai/examples/water-filling?ref=github) |

## More from ProvenDecisions on GitHub

- [optimization-tutorials](https://github.com/ProvenDecisions/optimization-tutorials): short lessons, the math explained line by line (new ones every month)
- [optimization-monthly](https://github.com/ProvenDecisions/optimization-monthly): the month's most eventful Daily Updates in optimization
- [provendecisions-api](https://github.com/ProvenDecisions/provendecisions-api): call the solver from your code or AI assistant

## Books

Our lecture notes as PDFs; read a free sample first.

- **[Convex Optimization: Concise Lecture Notes](https://proven-decisions.ai/books/convex-notes?ref=github)**: theory, algorithms and applications, about 175 pages. [Free sample: Chapter 1](https://proven-decisions.ai/books/convex-notes/sample.pdf?ref=github)
- **[Convex Optimization: Concise Lecture Notes, Solutions Manual](https://proven-decisions.ai/books/convex-solutions?ref=github)**: worked solutions to the exercises, about 100 pages. [Free sample: the solutions to Chapter 1](https://proven-decisions.ai/books/convex-solutions/sample.pdf?ref=github)

## Run locally

```
pip install cvxpy highspy jupyter
jupyter notebook notebooks/
```

## License

The code is under the [MIT License](LICENSE); the text and figures are under [CC BY 4.0](LICENSE-TEXT.md): reuse them, with credit to ProvenDecisions and a link to the page. The books and their samples are not covered: all rights reserved.
