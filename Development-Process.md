## Roadmap
The team has a 6 month high level [[Roadmap]] which defines high level themes and features to be addressed in this timeframe.

## Iterations
We will work in monthly iterations on the items on the roadmap. Iterations are roughly month based, rather than week based. We will begin a milestone on a Monday and end on a Friday, meaning that each milestone can have a different duration, depending on how the weeks align.

At the end of each iteration we want to have a version of Code that can be used by the Code community. The work planned during an iteration is captured in the iteration plan (see [[Iteration Plans]]). The feature highlights of each iteration are highlighted in the release notes.

## Planning

Before each milestone we will prioritize features to implement and bugs to fix in the upcoming iteration. Bugs are assigned the milestone for the iteration. For new features we create new issues and label them with `Plan Item`. Plan Items include a check list for the `Definition of Done`. The Bugs, Plan Items, and Feature Requests assigned to a milestone encompasses the planned work for the upcoming month. For each Plan Item we include the check list for b
 
### Definition of Done
- [ ] Test Plan Item created
- [ ] Key board accessible
- [ ] Screen reader accessible
- [ ] Works with the different themes, including the high contrast theme
- [ ] Telemetry events in place
- [ ] Release notes updated

## Inside an Iteration
We work in weekly segments:
- **Week 1**: Reduce debt introduced in the previous iteration, address critical issues uncovered in the previous iteration, plan the next iteration
- **Week 2**: Work according the plan
- **Week 3+**: Work according the plan
- **Final Week**: End game
  - the team tests the new features according a test plan and updates the documentation. 

## Triage
Bugs and features will be assigned a milestone and within a milestone they will be assigned a priority. The priority dictates the order in which issues should be addressed. A `important` bug (something that we think is critical for the milestone) is to be addressed before the other bugs. 

To find out when a bug fix will be available in an update, then please check the milestone that is assigned to the issue. 

Please see [[Issue Tracking]] for a description of the different workflows we are using.

## Weekly
Each week we will manage work items, crossing off completed features, and triaging bugs. At the end of the milestone we will strive for 0 bugs and 0 issues assigned to the milestone. Some bugs and features will then be either postponed to later milestones or moved back to the backlog.

## End Game
The final week of the milestone is what we call the "end game". During this week we will wrap up any feature work, we will test using a test plan [[Iteration Plans]], and then we will fix the critical bugs for that milestone.

Before we publish builds we manually execute the [[Smoke Test]] on all supported platforms.
