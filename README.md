# CUMCM2024-C
本文探讨了基于贪心算法的农作物种植策略优化，结合 2023 年的数据，在复杂的约束条件下实现了种植方案的优化，并对相关问题进行了深入研究。

在问题一中，首先对数据进行预处理，补全智慧大棚的数据，并计算每种作物的利润。通过亩利润热力图和种植策略图直观展现了初始策略。由于线性规划复杂，选择了更高效的贪心算法，在不同条件下分别实现了 3761 万元和 9359 万元的总利润，但后者年利润波动大。

在问题二中，通过重构代码适应数据随年份的变化，并引入了最大销售量的概念来处理超产作物。最终求得 5224 万元总利润，成功解决了利润波动大的问题，并且策略更加多样化，避免市场饱和。

在问题三中，研究了作物的可替代性、互补性以及相关性，并引入价格弹性和豆科作物间作机制，最终提升了 23.6% 的总利润，达到 6458 万元。

本文采用了基于优先队列的贪心算法，在考虑模型复杂度和计算速度的同时，对农作物种植进行了有效优化。

**关键字**：最优化、贪心算法、优先队列、价格弹性、间作

本研究最终获得省一等奖

在此再次感谢两位队友