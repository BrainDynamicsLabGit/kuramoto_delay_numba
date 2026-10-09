Kuramoto model with delays running natively on numba. Delays are implemented as integer-step lookback into the full phase history array; before a node's delay window has elapsed, missing history is clamped to the initial condition (equivalent to assuming the system sat frozen at t=0 for all t<0).

Run run_delay.py to run it with delay

The plasticity mechanism (hebbian rewiring + homeostatic renormalization of connectivity in every step) is turned off by default, and comes from https://doi.org/10.7554/eLife.111716.1
