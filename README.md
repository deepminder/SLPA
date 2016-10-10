# SLPA
SLPA(Speaker-listener Label Propagation Algorithm)算法是一种社区发现算法，它是对LPA算法（标签传播算法）的拓展。

社区（community）定义：同一社区内的节点与节点之间关系紧密，而社区与社区之间的关系稀疏。

设图G=G(V,E),所谓社区发现是指在图G中确定nc(>=1)个社区C={C1,C2,...,Cnv},使得各社区的顶点集合构成V的一个覆盖。

若任意两个社区的顶点集合的交际均为空，则称C为非重叠社区（disjoint communities）;否则称为重叠社区（overlapping communities）。
