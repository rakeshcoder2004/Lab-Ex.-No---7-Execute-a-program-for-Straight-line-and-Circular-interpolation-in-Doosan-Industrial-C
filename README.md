Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-cobot
## Aim : To Execute a program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio.

## Components Required:

*Doosan Industrial Collaborative Robot

*DRL (Doosan Robotics Language) Studio Software

### Theory 
INTERPOLATION

Interpolation, which is necessary for any type of programming, consists of generating data points between given coordinate axis positions. Within the Machine Control Unit (MCU), a device called an interpolator causes the drives to move simultaneously from the start to the end of the command. The interpolator is either an electronic hardware device for a NC system, or a software program for a CNC system. An interpolator provides two functions:

It calculates individual axis velocities to drive the tool along the programmed path at the given feed rate.

It generates thousands of intermediate coordinate points along the programmed path between the start point and the end point of the cut.

During positioning, all programmed axes move simultaneously at the specified feed rates until each axis has reached its destination. All drives start together, but without an interpolator individual destinations are reached successively according to the path traveled. However, an interpolator coordinates these axis motions in such a way that the programmed path is constantly maintained from the beginning to the end of the movement.

Linear and circular interpolation are most commonly used in CNC programming applications:

Linear interpolation is used for straight-line machining between two points.

Circular interpolation is used for circles and arcs.

Helical interpolation, used for threads and helical forms, is available on many CNC machines.

Parabolic and cubic interpolation are used by industries that manufacture parts having complex shape such as aerospace parts, and...

## Procedure:

Manipulate the end effector as per the given configuration. Movement Should Initiate in P1 and progress till the end point. Travel path should be in sequence as stated below.

Linear Interpolation

Circular Interpolation

### output

![11](https://user-images.githubusercontent.com/74660507/174606101-ceefbb2f-1a5e-4b5c-98c4-b675ee6585cb.jpeg)

![12](https://user-images.githubusercontent.com/74660507/174606121-88446623-62de-4a8f-a844-83a673f0d56a.jpeg)

![5](https://user-images.githubusercontent.com/74660507/174606255-4fd8d036-91cb-4d18-8ca9-f5becb7ddf99.jpeg)

![2](https://user-images.githubusercontent.com/74660507/174606195-0a3b7eb5-ac6c-43c2-ae06-59b77e9cf6bd.jpeg)



### Results 

Thus,program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio is executed
