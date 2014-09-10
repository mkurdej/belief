Boost.BFT
======

Master:
[![Build Status](https://travis-ci.org/mkurdej/bft.svg?branch=master)](https://travis-ci.org/mkurdej/bft)
[![Coverage Status](https://coveralls.io/repos/mkurdej/bft/badge.png?branch=master)](https://coveralls.io/r/mkurdej/bft)

Develop:
[![Build Status](https://travis-ci.org/mkurdej/bft.svg?branch=develop)](https://travis-ci.org/mkurdej/bft)
[![Coverage Status](https://coveralls.io/repos/mkurdej/bft/badge.png?branch=develop)](https://coveralls.io/r/mkurdej/bft)

Belief functions theory (Dempster-Shafer theory) implementation in C++

Dempster-Shafer theory implementation in a Boost-like fashion.

Features:
* FRAME OF DISCERNMENT
    * type checking
    * cartesian product of frames (TODO)
* MASS function and its equivalents
    * belief function
    * commonality function
    * plausibility function
* TRANSFORMATION functions (to_*)
    * to_belief
    * to_commonality
    * to_mass
    * to_plausibility
* NORMALIZATION
* OPERATOR/RULE
    * conjunctive rule (normal | by commonality) (precise | random)
    * disjunctive
    * Dempster
    * adaptive (Dubois-Prade)
    * cautious (conjunctive) rule + bold (disjunctive) rule (Denoeux)
    * PCx5, others
* DECOMPOSITION
    * 
* DISCOUNTING
* CONTEXTUAL DISCOUNTING
