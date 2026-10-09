Kuramoto model with delays running natively on numba. Delays are implemented as integer-step lookback into the full phase history array; before a node's delay window starts, past is constant (clamped at initial phases).

Run run_delay.py to run it with delay
