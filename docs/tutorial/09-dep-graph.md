# Step 9: Dep Graph

An Nx workspace can contain dozens (or hundreds) of applications and libraries. It can be difficult to understand how they depend upon each other, and what are the implications of making a particular change.

Previously, some senior architect would create an ad-hoc dependency diagram and upload it to a corporate wiki. The diagram isn’t correct even on Day 1, and gets more and more out of sync with every passing day.

With Nx, you can do better than that.

!!!!!
Run "npm run dep-graph". What do you see?
!!!!!
A dependency diagram in the browser
A dep-graph.html file created at the root of the workspace
A json document printed out in the terminal
