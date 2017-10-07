## Problem2:
### 1) What   would   your   first   steps   be   for   approaching   this   problem?

Each “reporter” can be treated as a noisy (and likely biased) sensor. Thus, a first step is to estimate the distribution of this noise and its bias. Moreover, sufficient data can give good estimates on average times for different tasks (moving containers within port, traveling accross the pacific, etc.). 

The idea would be to use the inferred probabilistic distributions on our “sensors” and our “tasks” as priors to obtain the posterior of the actual “state” (where it was when) of the system.

2) What   statistical   models   might   be   relevant   for   this   problem?

Without going into further details, this task looks very much like something a Kallman Filter could tackle. 