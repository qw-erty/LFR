# Line Following Robot

The line follower robot is an automated vehicle that follows a visual line embedded on the surface. This visual line is a path on which the line follower robot runs. Generally, it uses a black line on a white surface, or you can adjust it as a white line on a black surface.

## Working of Line Follower Robot

The concept of the line follower robot is related to light. Here, we use the behaviour of light on the black and white surface. The white colour reflects all the light that falls on it, whereas the black colour absorbs the light.

In this line follower robot, we use IR transmitters and receivers (photodiodes). They are used to send and receive the lights. When IR rays fall on a white surface, it is reflected towards IR receiver, generating some voltage changes.

When IR rays fall on a black surface, it is absorbed by the black surface, and no rays are reflected; thus, the IR receiver doesn’t receive any rays.

In this project, when the IR sensor senses a white surface, an Arduino gets 1 ( HIGH ) as input, and when it senses a black line, an Arduino gets 0 ( LOW ) as input. Based on these inputs, an Arduino Uno provides the proper output to control the bot.

## Components Used

>Arduino Uno 
>IR sensor 
>L293D motor driver 
>BO motor 
>Wheels 
>Lithium-ion battery 
>Jumper cables 
