# Research Review
_By Martin Strandbygaard_

_September 10th, 2017_

This short review describes three historical developments in the field of AI planning and search, and their impacts on the field of AI as a whole, as well as planning and seach.

1. Markov Decision Processes [1]
2. Stanford Research Institute Problem Solver (STRIPS) [2]
3. Planning Domain Definition Language (PDDL)

## Markov Decision Processes (MDP)
Markov Decision Processes {MDP) are used to model situations with partly random outcomes that are partly under the control of the decision maker. MDP has been know since the early 1950's, and a significant of the research on MDP resulted from Ronald A. Howard's book [1] published in 1960 [2]. MDP is an extension of Markov chains with the addition of actions, and rewards [2].

Markov Decision Processes has become a fundamental framework for probabilistic planning [3] and is also used in many other domains such as _reinforcement learning_ [4] and _learning automata_ [5]. Reinforcement learning is an important topic in the field of neural networks, and especially within the field of deep learning. 

## Stanford Research Institute Problem Solver (STRIPS)
The Stanford Research Institute Problem Solver (STRIPS) [6] was developed by Richard Fikes and Nils Nilsson in 1971 at SRI International [], and has since become the base for most other modern languages for expressing automated planning problem instances, commonly known as action languages [7].

STRIPS is a planning technique that works by first describing the world in terms of objects, actions, preconditions, and effects, and then executing the domain and problem to find a goal.

As such the greatest impact of STRIPS was not the automated planner itself, rather it has been the overall framework that STRIPS defined to solve problems in planning, and which has since then inspired much other resaerch in AI and planning specifically [6].


## Planning Domain Definition Language (PDDL)
The Planning Domain Definition Language (PDDL) [8] was develop it 1998 to enable the International Planning Competition (IPC) possible [9], and has since then remained the standard for IPC. 

The goal of PDDL was to provide a common formal language for describing planning domains. This makes in easier compare and contrast research, allows for more direct comparisons, and better enables sharing and re-use of research. PDDL is often used as the language of choice for a STRIPS.

PDDL has evolved since the first version was introduced, and the latest version is v3.1.

It has also seen a number of successors and variants, such as PDDL+ , NDDL (New Domain Definition Language), MAPL (Multi-Agent Planning Language), and others.


# References
[1] Howard, Ronald A. (1960). Dynamic Programming and Markov Processes

[2] https://en.wikipedia.org/wiki/Markov_decision_process

[3] Probabilistic Planning with Markov Decision Processen (https://www.microsoft.com/en-us/research/wp-content/uploads/2016/12/MDPs_Tutorial.pdf)

[4] Sutton, R. S.; Barto, A. G. (1998). Reinforcement Learning: An Introduction

[5] Narendra K., Thathachar M.A.L. (July 1974). "Learning automata – a survey"

[6] Richard E. Fikes, Nils J. Nilsson (Winter 1971). "STRIPS: A New Approach to the Application of Theorem Proving to Problem Solving"

[7] https://en.wikipedia.org/wiki/STRIPS

[8] McDermott, Drew; Ghallab, Malik; Howe, Adele; Knoblock, Craig; Ram, Ashwin; Veloso, Manuela; Weld, Daniel; Wilkins, David (1998). "PDDL---The Planning Domain Definition Language"

[9] http://ipc.icaps-conference.org/

