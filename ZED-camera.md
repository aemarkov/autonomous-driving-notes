# Zed-camera

Стерео-камера + софт. Возможности:
- [[SLAM]] (VIsual Odometry). Вроде неплохой
- Depth, включая [[Depth DNN]] Алгоритм хз. Вроде как совмещает классический stereo matching и DNN. Обещают дальность до 20 м.
- 3D Mapping
- [[Object detection]] (только ZED2)
- [[Object tracking]] (только ZED2)

Как по мне, так depth/point cloud отстойные. Даже с использованием режима DNN и режима заполнения пропусков в облаке.

Ожидание:
![[zed_depth_fill.jpg]]

Реальность
![[zed_depth_real.jpg]]


## References
- https://www.stereolabs.com/