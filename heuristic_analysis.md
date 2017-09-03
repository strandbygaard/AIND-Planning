# Heuristic Analysis

_Optimal plan for problems 1, 2 and 3_

_Compare and contrast non-heuristic search result metrics (optimality, time elapsed, number of node expansions) for Problems 1,2, and 3. Include breadth-first, depth-first, and at least one other uninformed non-heuristic search in your comparison; Your third choice of non-heuristic search may be skipped for Problem 3 if it takes longer than 10 minutes to run, but a note in this case should be included_

_Compare and contrast heuristic search result metrics using A* with the "ignore preconditions" and "level-sum" heuristics for Problems 1, 2, and 3._

_What was the best heuristic used in these problems? Was it better than non-heuristic search planning methods for all problems? Why or why not?_

_Provide tables or other visual aids as needed for clarity in your discussion._


## Uninformed Planning Searches

### Air Cargo Problem 1 Results

| Algorithm                          | Node  Expansions | Goal Tests | New Nodes | Length | Time [s] | Optimal |
|------------------------------------|:----------------:|:----------:|:---------:|:------:|:--------:|:-------:|
| Breadth-first                      |                  |            |           |        |          |   True  |
| Depth-first                        |                  |            |           |        |          |  False  |
| Uniform cost                       |                  |            |           |        |          |   True  |
| A* Search (h_1)                    |                  |            |           |        |          |   True  |
| A* Search (h_ignore_preconditions) |                  |            |           |        |          |   True  |
| A* Search (h_pg_levelsum)          |                  |            |           |        |          |   True  |

### Air Cargo Problem 2 Results

| Algorithm                          | Node  Expansions | Goal Tests | New Nodes | Length | Time [s] | Optimal |
|------------------------------------|:----------------:|:----------:|:---------:|:------:|:--------:|:-------:|
| Breadth-first                      |                  |            |           |        |          |   True  |
| Depth-first                        |                  |            |           |        |          |  False  |
| Uniform cost                       |                  |            |           |        |          |   True  |
| A* Search (h_1)                    |                  |            |           |        |          |   True  |
| A* Search (h_ignore_preconditions) |                  |            |           |        |          |   True  |
| A* Search (h_pg_levelsum)          |                  |            |           |        |          |   True  |

### Air Cargo Problem 3 Results

| Algorithm                          | Node  Expansions | Goal Tests | New Nodes | Length | Time [s] | Optimal |
|------------------------------------|:----------------:|:----------:|:---------:|:------:|:--------:|:-------:|
| Breadth-first                      |                  |            |           |        |          |   True  |
| Depth-first                        |                  |            |           |        |          |  False  |
| Uniform cost                       |                  |            |           |        |          |   True  |
| A* Search (h_1)                    |                  |            |           |        |          |   True  |
| A* Search (h_ignore_preconditions) |                  |            |           |        |          |   True  |
| A* Search (h_pg_levelsum)          |                  |            |           |        |          |   True  |
