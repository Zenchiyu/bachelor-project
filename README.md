# Bachelor Project: Implementation of learning methods inspired by reinforcement learning for symmetric rendezvous problem on the line

## Project outline and symmetric rendez-vous problem on the line
In the last semester, my bachelor project focused on the symmetric rendez-vous problem on the line where methods were inspired by reinforcement learning.
In the open problem, two blind agents (decision-makers) are on an infinite line and want to meet as fast as possible in expectation (speed bounded) without the possibility of sharing their positions. The problem is also symmetric : both agents follow the same stochastic strategy/policy.

Examples of applications of the generalized problem: search and rescue, meeting in an unknown territory for parachutists

Outcomes:
Although the project did not improve the current bounds on the optimal expected meeting time, it showed that there are possible directions to explore by learning a symmetric strategy from experience or interaction with an environment

---
## Disclaimer

The code might not work out of the box as it was created in google colab.

---

## Project structure

```
.
├── README.md
├── documentation
│   └── NguyenStephaneProjetBachelorRapport.pdf
├── notebooks
│   └── Simuler_strategies_probabilistes_bornees.ipynb
└── results
    ├── all_policies_update_except_K7M1_iter_10001.pkl
    ├── all_policies_update_except_K7M1_iter_10001_multiple_runs_no_two_phases.pkl
    ├── all_policies_update_except_K7M1_iter_10001_no_two_phases_reinforcing_last_sub_trajs.pkl
    ├── all_policies_update_except_K7M1_iter_2501_multiple_runs.pkl
    ├── all_policies_update_except_K7M1_iter_50001_no_two_phases_reinforce_gradient_projection_like.pkl
    └── policies_update_up_to_K3M2_iter_2501_with_expected_meeting_times.pkl

3 directories, 9 files
```

- `./documentation` contains my bachelor project report written in French as well as presentation slides
I did for another course.
- `./notebooks` contains one of the notebooks I wrote for my bachelor project
- `./results` contains a few results I obtained for the project (not all, no images)

## Credits

