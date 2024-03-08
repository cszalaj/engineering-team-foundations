# Committing and Merging Expectations #
We do not currently have clear expectations for the Engineering group that define expectations for daily work, committing code and merging branches. Setting clear expectations helps team members delivery higher quality work with more confidence. This proposal outlines basic guidelines for committing and merging work.  

# Contributors
This proposal was created by Chris Szalaj, with input from Engineering Leadership and a panel of engineers including Jon Cook, Rick Dailey, Yuri Uchida, Micah Parlato, and Josh TerAvest. 

## Proposal details
The manner in which and frequency that engineers interact with repositories is an important aspect of software development. It demonstrates how engineers think about building solutions and breaking down work, protects code from unexpected loss, and regularly shares work across the team. The following points are designed to give foundational guidance on expectations related to committing and merging code. Adhering to these foundations will help improve quality and avoid returns from points downstream in our work value streams, protect work from unexpected loss, and encourages engineers to thing about their work in smaller manageable units. 

### Committing Code ###
* All work in progress should be committed to a branch and pushed to the remote repository a minimum of once per day.
* Any code modified during a work day should be committed before the engineer signs off for the day, including completed tasks and partially completed tasks. If work is not yet ready to be officially merged, it can be committed to a personal branch so that the work is available to the rest of the team in the event the engineer has an unplanned absence or their local drive becomes unavailable. This ensures the most work that is ever at risk of being lost is equal to a days worth of work.
* Ideally, engineers will make multiple, small, iterative commits and remote pushes throughout the day across their tasks. This makes reviewing pull requests simpler, merging work easier, and further protects work from unexpected loss. 

### Branches ###
All teams should have a documented practice for working with and handling branches. Further foundation guidance will be introduced as branch-based development becomes more accessible to all teams.

At a minimum, today:
* All work should be conducted in a branch.
* All branches should exist both locally and remotely so that work is secured.

### Merging Code ###
Prior to submitting a pull request to merge a branch:

* Review the Jira card(s) for the branch's work to make sure all main success scenarios, test case scenarios and requirements in the card are met. 
* Code should have 100% unit test coverage of features added or modified in the branch. Make sure that all unit tests pass.
* Build the branch to ensure there are no build errors and that the branch runs on your local system.
* Test your changes to ensure your changes are applied and functioning as you expect.
* Write documentation that may be necessary to run your branch and its changes, and make it available to those reviewing your pull request.