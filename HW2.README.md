
# PUS2022 - HW2 - Research Hypothesis

This part of HW2 is aimed at presenting a research hypothesis relevant to my graduate research.

## General Idea

Microgrids are modular, local-scale, and potentially interconnected energy systems which are especially well-suited to supporting the integration of renewable energy into power grid infrastructure. They are increasingly considered as the building blocks of 'distributed energy systems', which are expected to play a key role in sustainability transitions and the development of carbon-neutral energy systems. The sourcing and distribution mechanisms that microgrids use are expected to play a key role in their ability to efficiently (1) incentivize sufficient locally-sourced energy to, at a minimum, meet local demand, and (2) coordinate local supply with local demand (temporally, at a minimum) to support both 'market' efficiency and power system stability. 

Currently, local energy markets are considered a key approach to sourcing and distribution in systems where generation resources are not directly controllable by power grid operators -- such as in micgrogrids which aim to utilize residential and other independently-owned renewable energy resources. The current 'state of the art' approaches in local energy market design utilize double-sided auction mechanisms to define energy sourcing and distribution -- but these mechanisms in general have recently been shown to be incapable of aligning efficient techno-economic performance with the requirements of emerging energy equity standards for energy infrastructure development and operations. Accordingly, there is a strong and imminent need for the definition of 'market' (sourcing and distribution) mechanisms which can align energy system outcomes with equity standards. But as of yet, no such mechanisms have been clearly demonstrated in the literature. 

> **A general hypothesis of my thesis project is that there is no inherent trade-off between outcome expectations related to energy equity and techno-economic performance**

In other words, that there exists sufficiently-general mechanisms, which may be applied to a sufficiently-diverse range of microgrid operation scenarios, which can simultaneously achieve both sets of requirements consistently, independent of system scale and 'stage' of energy system transition. I intend to construct this 'proof of existence' by presenting and analyzing sufficiently-generalized example mechanisms which satisfy the 'goal alignment' criteria in ways which are practically (spatially, economically, legally, etc) feasible for real-world implementation. If successful, project results can be expected to provide substantial support for the establishment of equity standards for energy infrastructure development and operations, and for further development of community-sourced, owned, and guided solutions to sustainable energy transition.

</br>

***Update: The use of testable examples for mechanisms expected to be 'equitable' (in terms of outcome assessment) allows a more explicitly-testable version of the hypothesis to be formed:***

> **The mechanisms presented, which are defined using techno-economic and equity-based constraints, represent examples of coordination mechanisms (or 'market' mechanisms) for local energy systems which can be expected to ***consistently*** align techno-economic and equity-related expectations (that is, simultaneously satisfy both sets of expectations)**

_If the hypothesis is confirmed, one conclusion may be that there is no inherent trade-off between these sets of outcome expectations for local energy system (LES) coordination mechanisms -- suppoorting the establishment of policy-based regulations regarding mechanism use in real-world LES development, and an extended set of theoretical design requirements for LES mechanism design engineering._

</br>

## Null Hypothesis

Example local energy 'market' mechanisms fail to consistently satisfy one or more of the considered techno-economic and equity-related performance indicators -- either across time or system operation conditions (e.g. microgrid energy supply-base size, the size of local energy demand, the number of microgrid users, temporal alignment of supply and demand).

</br>

## Alternate Hypothesis

Example local energy 'market' mechanisms consistently satisfy each of the considered techno-economic and equity-related performance indicators, across time, independent of factors such as microgrid energy supply-base size, the size of local energy demand, the number of microgrid users, and the temporal alignment of supply and demand.

</br>

## Comments on Experimental Design

Performance indicators are defined to include key technical, techno-economic, and socio-economic expectations for 'market' operations. For example, a technical indicator is the "power flatness index" (ratio of supply to demand locally); a techno-economic indicator is market efficiency (technical, not allocative); and a socio-economic indicator is household-level individualized energy affordability. Techno-economic indicators are mainly used to evaluate expected game-theoretic properties of mechanisms, while socio-economic indicators are derived from a minimally-sufficient set of requirements for energy equity satisfaction (which are themselves derived to satisfy requirements for ethical justification of 'market' operation and outcomes according to a fairness/justice approach, a standard approach in environmental justice and related research).

There may be a conceptual issue with this hypothesis as it currently stands, on the basis of falsifiability. If the project results fail to support rejection of the null hypothesis, it doesn't mean that there IS an inherent trade-off between techno-economic performance requirements and energy equity requirements in local energy 'market' mechanisms, it just means that the mechanism designs presented in the project are not in fact examples of such mechanisms. It wouldn't mean that these mechanisms don't exist at all! Nevertheless, this could be a problem for falsifiability, or consistency between the actual hypotheses and how they're represented in 'plain language' (e.g. in the General Idea section).

Mechanism testing will be conducted in an agent-based simulation environment. Needed pieces of simulation modeling include a dynamic and sufficiently-realistic approach to representing household energy demands. In this course (SPPA 667), I hope to use the term project as an opportunity to apply data science methods to produce an efficient, stochastic model of household energy demand which may be used to generate spatio-temporally realistic energy demand values for simulated households. I want to learn a set of key features (or 'principal components') in energy data which can be used to derive effective learning models of household energy use, and I'm hoping that learning a 'sampling distribution' based on these key features involved enough 'ML / DS' to qualify as a good project for the course! If not, I'll be very interested to explore how the idea can be extended!
