| - | classical algorithm | heuristic algorithm | gradient descent algorithm |
| - | - | - | - |
| Time | 1930s | 1970s | 1980s |
| Complexity | simple | middle | high |
| Deterministic | Yes | No | No |

Monte Carlo algorithm
+ Base on random

Heuristic algorithm
+ Continuous, Discrete
+ Problem dependent, problem independent (meta)
+ Algorithms
  + Climbing -> One initial find local best 
  + Tabu -> One initial find local best + hash table (key:state, val:fobidden times) evaluate all loss(neighbor) if smaller loss and in hash table, then forbidden minus 1. Delete state from forbidden if forbidden==0 
  + Annealing -> One initial find probability(local best, worse) which P decay along with time (exp(-deltaC/T0))
  + Gene 
  + Ant
