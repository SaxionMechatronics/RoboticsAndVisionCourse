# Robotics and Vision Course

This is the robotics and vision course repository. It contains a curated list of interesting links in the field of robotic development. In addition, code snippets will be provided to assist in the understanding of various topics.

Henk Kortier 2019

## Links

---

### Software Development

#### Linux USB pendrive

----

**THIS PART IS UNDER DEV!!!**

There are two options for preparing a USB pendrive with linux/ros.
Always try option 1 first!

1. Ready-to-use uefi-linux-ros distro:
   1. Use [balena ether](https://www.balena.io/etcher/) to flash an image to an USB stick.
   2. Use the following [image](https://www.dropbox.com/s/2ychkkd6a3p0237/verbatim_ubuntu_uefi.img?dl=0) (xenial-kinetic)
   3. Set your BIOS to UEFI mode, disable boot security stuff
   4. Try to boot from the stick (give priority in the bios if necessary)

2. Try the steps described in the following forum post if the first nethod didn't not work. You'll need two USB sticks; one with the live distro and one to install the distro onto. This method installs vanilla xenial. Hence, you still need to install ROS and supporting packages.
   1. Prepera a USB stick with the default live distro (white saxion)
   2. Use these [instructions](https://askubuntu.com/questions/16988/how-do-i-install-ubuntu-to-a-usb-key-without-using-startup-disk-creator/942312#942312) to install a permanent distro to a second USB stick (verbatim)

**THIS PART IS UNDER DEV!!!**

----

#### Editor

- [Visual Studio Code editor](https://code.visualstudio.com)

#### GIT

- [GIT intro](https://www.slideshare.net/YanVugenfirer/introduction-to-git-69958365)
- [GITHUB for beginners](https://www.slideshare.net/HubSpot/git-101-git-and-github-for-beginners)
- [Essential Skills for reproducible research, UNIX, GIT, PYTHON](https://barbagroup.github.io/essential_skills_RRC/)

---

### Robotics

---

#### Generic

- [Robot academy](https://robotacademy.net.au)
- [Peter Corke RVC Book and Toolbox](http://petercorke.com/wordpress/)

#### ROS

- [Robotis ROS book](http://www.pishrobot.com/wp-content/uploads/2018/02/ROS-robot-programming-book-by-turtlebo3-developers-EN.pdf)
- [Delft MOOC](https://online-learning.tudelft.nl/courses/hello-real-world-with-ros-robot-operating-systems/)
- [Ros Industrial Training](https://industrial-training-master.readthedocs.io/en/kinetic/)


#### OpenManipulator platform

- [OpenManipulator](http://emanual.robotis.com/docs/en/platform/openmanipulator_x/overview/)
- [MATLAB: Openmanipulator, controlling robot manipulator joints](https://www.youtube.com/watch?v=cmgOqrd2yiY)

