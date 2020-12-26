# LeGO-LOAM
Category: [[SLAM]]

[[LiDAR]]-based [[SLAM]]. Вариация известного алгоритма  [[LOAM]], ориентированного на использование в наземных роботах.

Особенности:
- Выделение поверхности (земли) и навигационных фич, на основе предположения, что робот двигается в плоскости по земле
- За счет этого меньше всякого мусора считается фичами, стабильнее одометрия
- Также меньше точек и фич, быстрее работает. Работает на [[Jetson TX2]]
- Loop Closing

## References
- https://github.com/RobustFieldAutonomyLab/LeGO-LOAM
- [[LeGO-LOAM Lightweight and Ground-Optimized Lidar Odometry and Mapping on Variable Terrain.pdf]]
- Доклад: https://youtu.be/JsHac3h2CIA
- Сайт этих чуваков (универа): https://robustfieldautonomylab.github.io/

