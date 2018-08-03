# Protocol Canvas
The Protocol Canvas is a means of mapping primitives between actors within a decentralized protocol. Derived from the [Business Model canvas](https://strategyzer.com/canvas/business-model-canvas), the Protocol Canvas is designed for decentralized systems and fully open sourced.

## Overview
Designing decentralized systems brings into context some novel areas of research and development, such as crypto-economics, token design, decentralized protocol architecture, and token engineering. In addition, there are a lack tools for entrepreneurs, engineers, product managers & designers to express and optimize their protocol designs.

The Protocol Canvas is a tool for ‘Protocol Designers’ to help design a new decentralized system. The canvas can also be used to deconstruct existing decentralized systems to identify design gaps and to improve its future design. **Whitepapers** can efficiently leverage this canvas to clearly communicate their protocol design to a discerning audience of engineers, investors and token holders.

## Using The Canvas
Mechanism design is a sub-discipline of economics dedicated to studying how to design protocols that incentivize rational actors to behave in socially desirable ways.

In game theory, we take the game as a given and analyze its outcomes according to players’ utilities, whereas mechanism design allows one to start by defining desirable outcomes and work backwards to create a game that incentivizes players towards those outcomes.

The principle of mechanism design is a driving factor in approaching the design of decentralized protocols.

## Objectives & Decentralized Protocol Primitives
The primary objective is to capture the participating network actors' mappings to the system's Decentralized Protocol Primitives (DPPs).

- Identify the network **Actors** & their roles
- List what their top 'value adds' are to the network to capture their **Desired Behaviors**
- Create **Incentives** to extract the actors' desired behaviors
- Lay out deterministic and probabilistic outcomes for pre-defined rulesets
- Identify points of failure as **Risk Factors** associated with each actor
- Explore what **Governance** measures (eg. staking & slashing) can be applied to mitigate risks
- Map out the Risks vs Rewards

Some examples for Actors are:

- Miners (Ethereum)
- Makers & Takers (0x)
- Reporter (Augur)
- Curator (TCRs)

Some examples for DPPs are:

- Desired behaviors
- Incentives
- Risk Factors
- Rewards
- Governance
- Security
- Trust
- Points of failure

Incentives can refer to activities such as block rewards, and earning tokens.
Staking & slashing can be considered as governance measures.

As many canvases are built and the design is mapped out, some interesting observations start forming:

- dApps center around designs that risk vs reward for actors while protocols identify risks & mitigate them through network incentives
- protocols work on commitment in the future based on performance in the past
- risk <> reward structures keep all actors on edge and accountable
- block rewards are ideal for proven resource contribution

## Putting it all together
What we end up with is mapping all of this in a matrix - the Protocol Canvas.

![protocol-template](/assets/protocol-template.PNG)

## Contributions
The mission here is to help individuals and organizations capture their design in a standardized way and to contribute towards the new discipline of Token Engineering.

We're looking for contributors to submit their protocol design, add new DPPs, and help optimize the Protocol Canvas own usability.

- Fork the repo
- Use the template from TEMPLATE.md
- Create a new file name named <protocol-name>.md under the 'canvases' folder.
- Submit a PR!

For any questions / feedback, please use the issues area. Happy to engage and work with you :)
