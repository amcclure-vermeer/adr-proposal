# 38. RFC and final decision process for ADRs

Date: 2024-03-06

## Summary
In the context of allowing more opinions to be heard and addressed in the decision-making and publishing of ADRs,
we decided {decision},
and neglected {alternatives},
to achieve {positive consequences},
accepting the downside of {negative consequences}.

## Status
Proposed

## Context
There is no current open and publicized process for ADRs to be proposed and discussed before a decision is made.
While the final decision-making would be left to the architecture committee, it is important to have a process that allows for more input from the engineers and developers who are affected by the decisions.
Allowing these parties to voice their opinions, concerns, and ideas should lead to better decisions and more buy-in from the individuals and teams that will be implementing the decisions, as well as helping to garner more interest in the outcomes of these decisions.

## Considered Options

### No RFC Process

The architecture committee will continue to make decisions without direct input from the developers and engineers.

#### Pros
* Fastest process
* Smaller group with fewer options to consider
* Less overhead

#### Cons
* Less buy-in from the teams
* There could be options or considerations missed
* Less transparency before a decision is made

### GitHub Pull Request

ADRs are proposed as a pull request (PR) to the `v-adr-project` repository. 
The proposal is neutrally announced during the next available tech leveling meeting covering the context of the proposed ADR, where it then enters a Request for Comments (RFC) period of at least one week.

The comments of the PR will be used to discuss the proposed ADR, with the ability to propose changes to the context and options. The ideas and concerns can be gauged by responses and discussion in the comments and should be weighed appropriately by the architecture committee when making a final decision.

A one day warning will be given before the RFC period ends, and the final decision will be made by the architecture committee.

#### Pros
* Allows for more direct input from the developers and engineers
* More ideas and concerns can brought forward that may not have been considered by a smaller group
* More transparency on addressing the wider concerns of a decision in the `Consequences` section 
* Asynchronous process in which a meeting does not need to be attended to voice an opinion

#### Cons
* More overhead and process
* Longer process before an ADR is accepted
* More opinions to consider can make for more difficult decision-making

### ADR proposal open forum

The architecture committee will hold an open forum for the developers and engineers to voice their opinions, concerns, and ideas on the proposed ADRs.
The committee will then make a final decision after the open forum.

#### Pros
* Allows for more direct input from the developers and engineers
* More ideas and concerns can brought forward that may not have been considered by a smaller group
* More transparency on addressing the wider concerns of a decision in the `Consequences` section
* Can be easier to have a discussion in real-time
* Less overall time than the PR process

#### Cons
* Another meeting
* Requires all interested parties to be able to attend the meeting in order to make their opinions heard
* More opinions to consider can make for more difficult decision-making

## Decision


## Consequences

