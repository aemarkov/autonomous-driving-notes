# Traversability
"Проходимость". Разные способы определять, где робот может пройти, а где нет. 

Определение проходимости для неплоской поверхности (см. [[Sidewalks robot]], [[Autonomous delivery]]). 

Классификация:
- Classification (можно проехать/нельзя)
- Regression (стоимость или иная метрика проезда)

1. Строим 3D модель поверхности, используем регрессию или классификацию классическими методами: определяем наклон, высоту, stddev [1]. Тут нам нужна большая разрешающая способность (?)  трехмерной карты. Классический [[LiDAR]] не подойдет. [[LiDAR Solid State]] или [[Depth camera]]?
2. Всякий machine learning


## References:
1. [[Autonomous Navigation on Urban Sidewalks Under Winter Conditions]]
2. [[Terrain Classification for Mobile Robots on the Basis of Support Vector Data Description]]

