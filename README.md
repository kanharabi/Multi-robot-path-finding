# Multi-robot-path-finding
CBS
[Multi Agent Path Finding] Consider a warehouse and a set of robots which pick up items from

designated places, deliver those in desired locations, and finally the robots go to the end lo-
cation. Assume that the warehouse is represented as a 2-D grid of size n × m. Each location
(Li) on warehouse floor can be denoted by a pair of integers Li = (xi, yi). Each cell on the
grid can be categorized in one of the following ways (see diagram below) - source location (P1-
P3), destination location (D1-D3), temporary storage location (TS1-TS4), obstacle (black square),
normal (rest of the cells). Source & destination denote pick-up and drop locations respectively.

Temporary storage location denotes the place where robot can keep some items. Obstacle rep-
resents a location where no robot can move. Rest of the cells are considered as normal cell.

Let there be k number of robots and r number of tasks. The details of robot location and tasks
are provided as per the following table.

Assume that the a robot can move at most one cell (either vertically or horizontally) at a time
step, a normal cell can be occupied by at most one robot. Source, destination, temporary stor-
age locations can accommodate multiple robots simultaneously. Our target here is develop a
work schedule that minimizes the time to complete all tasks. You need to develop both optimal
as well as heuristic algorithms.
