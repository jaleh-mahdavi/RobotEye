# RobotEye
In this project, I designed a software architecture named “robot eye”. The Robot Eye
system contains a robot which holds a camera and can move around a room either
manually or automatically by a command received from a web server or a mobile device
users . Also, the user of the mobile device can ask for current position of the robot either
directly or by asking the camera to take a picture or video. Also, a web client can ask for
current position of the robot through internet by sending a command to the camera to
take a photo or video.

In addition, my design supports the four quality attributes which are important for
stakeholders of this design named modifiability, security for internet users, usability and
performance. As a result, any new changes can be done in my system easily. Also, users
can interact with both mobile device and web simply and effectively. Moreover, latency
between receiving a command for movement of the robot and actual robot motion,
taking a photo/video and viewing a taken photo/video should be limited.

I documented my design using UML Composite Structure diagram in order to describe
overall software architecture, Class diagram to show modules/components of
subsystems, Sequence diagram to show collaboration, State Machine diagram to show
behaviors of components and Component and Deployment diagrams to show allocation
and deployment.
