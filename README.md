# Poorchestrator

tl;dr - 
Gets Claude to orchestrate batches of issues by commenting "@claude please implement" in an sensible order.

nl;ir - 

On calling /orchestrate, the agent surveys open PRs and issues, planning the best order to complete and merge ongoing work.
It then invokes the architect agent to update issues with Architecture Reference Notes (ARNs) to aid compatibility following parallel implementation.
Continues until everything is merged. 

Architecture-driven development is the future.

