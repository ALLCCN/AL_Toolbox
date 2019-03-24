# Weighted random selector

## input
- candidates: array, a list of candidates;
- candidate: object
- candidate.name: string
- candidate.weight: number
- maxProbability: number, the max percentage of a candidate that can be chosen in this system, not less than 1/n
- minProbability: number, the min percentage of a candidate that can be chosen in this system, not higher than 1/n

## output
- candidate.prob: number, the probability of this candidate chosen in this system

## Pseudocode

