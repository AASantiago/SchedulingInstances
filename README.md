# Scheduling instances used in: GRASP and Iterated Local Search Based Cellular Processing Algorithm for Precedence-Constraint Task List Scheduling on Heterogeneous Systems

This parallel DAGs are also studied in:

Carlos Soto, Alejandro Santiago, Héctor Fraire, Bernabé Dorronsoro (2018). Optimal Scheduling for Precedence-Constrained Applications on Heterogeneous Machines, Proceedings of MOL2NET 2018, International Conference on Multidisciplinary Sciences, 4th edition, 1 (doi: 10.3390/mol2net-04-05925).

Aurelio A. Santiago Pineda, Johnatan E. Pecero, Héctor J. Fraire Huacuja, Juan J. Gonzalez Barbosa, Pascal Bouvry (2013). An Iterative Local Search algorithm for scheduling precedence-constrained applications on heterogeneous machines. In Multidisciplinary International Conference on Scheduling: Theory and Applications (MISTA), 2013.

J. E. Pecero, H. J. F. Huacuja, P. Bouvry, A. A. S. Pineda, M. C. L. Locés and J. J. G. Barbosa, (2012). On the energy optimization for precedence constrained applications using local search algorithms. International Conference on High Performance Computing & Simulation (HPCS), Madrid, 2012, pp. 133-139.

The instances use the following format:

#critical\
0.000\
#tasks\
0: 11.00, 13.00, 9.00\
1: 10.00, 15.00, 11.00\ 
2: 9.00, 12.00, 14.00\
3: 12.00, 16.00, 10.00\
4: 15.00, 11.00, 19.00\
5: 13.00, 9.00, 5.00\
6: 11.00, 15.00, 13.00\
7: 11.00, 15.00, 10.00\
#edges\
0:  0,  1,  11.00\
1:  0,  2,  17.00\
2:  0,  3,  14.00\
3:  0,  4,  11.00\
4:  1,  5,  13.00\
5:  2,  5,  10.00\
6:  3,  5,  19.00\
7:  3,  6,  13.00\
8:  4,  6,  27.00\
9:  5,  7,  21.00\
10: 6, 7, 13.00\
#end\

The first Section #critical can be ignore (not computed in most cases). The second Section #tasks represents the computing time units in the machines starting from the machine 0 and ending at the machine k-1. The third Section represents the DAG edges: initial, ending, edge cost.
