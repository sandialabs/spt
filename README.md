# Sandia Simple Particle Tracking (Sandia SPT) v. 1.0

The computer code is designed as software to accompany a book chapter being published, a methods chapter which provides an introduction on how to label and track individual proteins. The Sandia Simple Particle Tracking code does not introduce new algorithms or techniques, but uses techniques common to the image processing community. Instead, the purpose and value of Sandia SPT is that it facilitates implementing the methods described in the book chapter by providing the necessary open-source code. The code performs single particle spot detection (or segmentation and localization) followed by tracking (or connecting the detected particles into trajectories). Sandia SPT is quite simple, totally under 200 lines of code. 

Sandia Simple Particle Tracking makes use of an open-source linear sum assignment problem solver (http://www.mathworks.com/matlabcentral/fileexchange/26836-lapjv-jonker-volgenant-algorithm-for-linear-assignment-problem-v3-0), an implementation of the Jonker-Volgenant Algorithm, to perform particle tracking. Sandia Simple Particle Tracking also makes use of an open-source Gaussian fitting routine, written by me in graduate school and released under the GPL.

Anthony, Stephen Michael

SCR# 1720
