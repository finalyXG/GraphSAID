# GraphSAID

#### Graphs are extensively employed in data mining and machine learning owing to their remarkable ability to model real-world objects and their relationships. However, as graphs scale up, they present several challenges. To tackle these issues, graph sampling methods have gained popularity by selecting a representative subgraph within a given budget. However, most graph sampling approaches rely on graph-structure information and cannot simultaneously consider node feature interaction and selection bias to perform graph sampling. Given the recent success of the attention mechanism in model training, it is worth investigating its potential to enhance graph sampling methods and overcome their challenges. The primary objective of this work is to establish a novel connection between the learned attention and the graph sampling problem using the Integer Programming method. To accomplish this, we propose a novel solution, GraphSAID, which utilizes an attention learning stage to generate initial node-level attention, followed by an aggregation stage to compute connected component scores that are independent of the budget. Finally, the Integer Programming method is employed to optimize an objective function that considers both the budget value and the user-defined selection bias. Empirical results on 1 synthesized and 3 real-world graph datasets demonstrate its superior performance. Additionally, we showcase the ease with which selection bias (user control) can be incorporated into GraphSAID to further improve performance.

