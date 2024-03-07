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
There is no current open and publicized process for proposing and discussing ADRs before a decision is made.
While the architecture committee will make the final decision, it is essential to have a process that allows for more input from the engineers and developers affected by the decisions.
Allowing these parties to voice their opinions, concerns, and ideas should lead to better decisions and more buy-in from the individuals and teams that will be implementing the decisions. It should also help garner more interest in the outcomes of these decisions.

## Considered Options

### No RFC Process

The architecture committee will make decisions with direct input from the developers and engineers.

#### Pros
* Fastest process
* Smaller group with fewer options to consider
* Less overhead

#### Cons
* Less buy-in from the teams
* There could be options or considerations missed
* Less transparency before a decision is made

### GitHub Pull Request

Propose ADRs as a pull request (PR) to the `v-adr-project` repository. 
The proposal is announced during the next available tech leveling meeting covering the context of the proposed ADR, where it then enters a Request for Comments (RFC) period of at least one week.

Use the PR's comment section to discuss the proposed ADR, with the ability to propose changes to the context and options. Responses and discussions in the comments can gauge ideas and concerns and should be weighed appropriately by the architecture committee when making a final decision.

A member of the architecture committee will give a one-day warning before the RFC period ends, after which the committee will make a final decision.

#### Pros
* Allows for more direct input from the developers and engineers
* More ideas and concerns can brought forward that a smaller group may not consider
* More transparency on addressing the broader concerns of a decision in the `Consequences` section 
* Developers and engineers do not need to attend a meeting to have their voices heard

#### Cons
* More overhead and process
* Longer process before an ADR is accepted
* More opinions to consider can make for more difficult decision-making

### ADR proposal open forum

The architecture committee will hold an open forum for the developers and engineers to voice their opinions, concerns, and ideas on the proposed ADRs.
The committee will then make a final decision after the open forum.

#### Pros
* Allows for more direct input from the developers and engineers
* More ideas and concerns can brought forward that a smaller group may not consider
* More transparency on addressing the broader concerns of a decision in the `Consequences` section
* It can be easier to discuss in real-time
* Less overall time than the PR process

#### Cons
* Another meeting
* Requires all interested parties to be able to attend the meeting to make their opinions heard
* More opinions to consider can make for more difficult decision-making

## Decision


## Consequences

