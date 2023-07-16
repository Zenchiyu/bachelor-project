
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PQ_DDKtybPYOu60aEphWkZo64BNJOjAH#scrollTo=3oHNhsAj_vgA)

# Bachelor Project (2021): A ML-inspired Approach to Symmetric Rendezvous Problem on the Line

## Project outline and symmetric rendez-vous problem on the line
In the last semester, my bachelor project focused on the symmetric rendez-vous problem on the line where methods were inspired by reinforcement learning.
In the open problem, two blind agents (decision-makers) are on an infinite line and want to meet as fast as possible in expectation (speed bounded) without the possibility of sharing their positions. The problem is also symmetric : both agents follow the same stochastic strategy/policy.

Examples of applications of the generalized problem:
- search and rescue, meeting in an unknown territory for parachutists

Outcomes:
- Although the project did not improve the current bounds on the optimal expected meeting time, it showed that there are possible directions to explore by learning a symmetric strategy from experience or interaction with an environment


---
## Disclaimer

The code might not work out of the box as it was created in google colab.

---

## Project structure

```
.
├── LICENSE
├── README.md
├── documentation
│   ├── presentation_slides.pdf
│   ├── project_report.pdf
│   └── project_summary.pdf
├── notebooks
│   └── Simuler_strategies_probabilistes_bornees.ipynb
└── results
    ├── all_policies_update_except_K7M1_iter_10001.pkl
    ├── all_policies_update_except_K7M1_iter_10001_multiple_runs_no_two_phases.pkl
    ├── all_policies_update_except_K7M1_iter_10001_no_two_phases_reinforcing_last_sub_trajs.pkl
    ├── all_policies_update_except_K7M1_iter_2501_multiple_runs.pkl
    ├── all_policies_update_except_K7M1_iter_50001_no_two_phases_reinforce_gradient_projection_like.pkl
    └── policies_update_up_to_K3M2_iter_2501_with_expected_meeting_times.pkl

3 directories, 12 files
```

- `./documentation` contains:
	- `./documentation/project_report.pdf`: Bachelor project report (in French)
	- `./documentation/presentation_slides.pdf`: Presentation slides explaining the problem and one particular paper (Han et al.)
	- `./documentation/project_summary.pdf`: 800 words summary explaining the project

- `./notebooks` contains one of the notebooks I wrote for my bachelor project
- `./results` contains a few results I obtained for the project (not all, no images)

## Credits

Han, Qiaoming et al. (June 2008). “Improved Bounds for the Symmetric Rendezvous
Value on the Line”. In: Operations Research 56.3, pp. 772–782. doi: 10.1287/
opre.1070.0439.

Gosavi, Abhijit (2014). Simulation-based optimization: parametric optimization techniques and reinforcement learning. New York: Springer. isbn: 978-1-4899-7490-7.
Luenberger, David G. and Yinyu Ye (July 2015). Linear and Nonlinear Programming. en. 4th ed. 2016 edition. Springer. isbn: 978-3-319-18841-6.

Sutton, Richard S. and Andrew G. Barto (2018). Reinforcement learning: an introduction. en. Second edition. Adaptive computation and machine learning series.
Cambridge, Massachusetts: The MIT Press. isbn: 978-0-262-03924-6.
