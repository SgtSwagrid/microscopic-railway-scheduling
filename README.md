# 🚂 Microscopic Railway Scheduling: Combining MIP and SMT through Clustering and Hypergraph Duality

The [text](Microscopic_Railway_Scheduling.pdf) for my Master's thesis at the ETH [Institut für Verkehrsplanung und Transportsysteme](https://www.ivt.ethz.ch/).

## Abstract

The schedules for passenger trains are (or should be) meticulously planned to
ensure that they are as good as they can be, given the available infrastructure.
Good scheduling is key in providing short travel times, high service frequencies,
and reliable connections, as well as in minimising unnecessary resource
consumption. This is a highly combinatorial problem: many trains must share
the same densely interlocking infrastructure, all while avoiding collisions and
maintaining passenger transfer possibilities.

Traditionally, rail scheduling is performed manually by human schedulers;
a practice that continues to this day.
There is, however, increasing interest in automated, algorithmic scheduling.
Existing approaches are usually variants of an [MIP](https://en.wikipedia.org/wiki/Integer_programming)
or [SMT](https://en.wikipedia.org/wiki/Satisfiability_modulo_theories) formulation.
Because the problem is [NP-hard](https://en.wikipedia.org/wiki/NP-hardness), these approaches break down for larger instances.
A novel approach is explored, whereby the problem is decomposed into smaller parts.
