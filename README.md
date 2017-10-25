# Ball-Tracking-Servo
A simple scene built in V-rep. A Robotic manipulator having 2 DOF is designed that tracks a Red Ball in 3D Space. A proportional
Controller is used for tracking. 2 revolute joints are used. 1 to rotate the the horizontal cylinder about its vertical axis of
symmetry and the other to rotate it about its horizontal axis. The joint velocities are plotted on the top right graph. The
location of the sphere is plotted on the bottom right graph in the video. The image seen by the camera is shown on bottom left. The
manipulator tries to keep the ball in the center of the view are. 

Video Link: https://www.youtube.com/watch?v=wxhTROs7QdA&t=2s
 
![Alt text](/Ball-Tracking-Servo/Screenshot from 2017-10-25 11-25-40.png?raw=true "Optional Title")
Proportional Controller:- Joint_velocity= K*(error) 
where, error= (Target_position-Actual_position) of the ball as seen by the camera.

V-rep Version- 3.4.0 
programming Language- Lua.
