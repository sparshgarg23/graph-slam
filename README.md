# graph-slam
in this project we implement SLAM that is used to estimate the location of the robot in an environment  and identify the locations of 
landmarks.
To impement graph slam  we need to keep in mind that Every time we make an observation, for example as we move between two poses by some distance dx and can relate those two positions, you can represent this as a numerical relationship in these matrices.
We are referring to robot poses as Px, Py and landmark positions as Lx, Ly, and one way to approach this challenge is to add both x and y locations in the constraint matrices.
A good source for reference is mentioned below
[A Tutorial on Graph-Based SLAM](http://www2.informatik.uni-freiburg.de/~stachnis/pdf/grisetti10titsmag.pdf)
