#学习记录 

## Opensim 肌骨模型

1. 骨骼模型：
	- 刚性骨头
	- 运动副
	- 约束
1. 肌肉：
	- 特殊力
2. 其他力：
	- PrescribedForce
	- BushingForce
	- ...

## 运动副

WeldJoint:
PinJoint:
SliderJoint:
BallJoint:
UniversalJoint:
EllipsoidJoint:
FreeJoint:
CustomJoint:

**人体正常情况下为树状模型，是开链的。但是如果我们引入了外骨骼或者康复机构会组成闭合运动链，这个时候就需要引入约束，形成闭环系统**
>这里还没有搞懂

Body有点类似于之前ROS中的urdf文件

运动副的定义，类似于机器人运动学

## XML文件
[[XML和OSIM文件详解]]

