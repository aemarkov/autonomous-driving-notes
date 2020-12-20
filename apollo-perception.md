[[Perception]]

Модуль восприятия (т.е. детектирования всякого) проекта [[apollo-driving]]

Sensors:
- [[camera]]
	- Две передние камеры с разным фокусным расстоянием
- [[radar]]
	- Передний и задний радар
- [[LiDAR]]
	- 128 лучевой лидар
	- Стопицот 16-лучевых лидаров (спереди, сзади слева, сзади справа)
	- [[Object detection 3D]] с моделью [[PointPillars Fast Encoders for Object Detection from Point Clouds]]
	- Tracking


Output:
 - 3D obstacle track with heading, velocity and classification ([[Object tracking]])
 - Traffic light detection

Как работает:
- Дектирование и трекинг с помощью лидара, камеры и радара, потом фьюжн
- Детектирование светофоров
- Детектирование полос