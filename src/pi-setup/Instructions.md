Base on which operating system you are running (Raspbian or Ubuntu).
Raspbian:
    You don't need to use run the files in the networking folder but you would need to go into the |dock| folder for installization
    of a Docker container for Robotic Operating System (ROS) and the version we are planning to use is ROS2 Humble Hawksbill, 
    for its stablity in future interations of the project and a long history of community support.

Ubuntu:
    You would need to have install Ubuntu Server 22.04 due to the Ubuntu Desktop is using up too much resources where it would be 
    laggy. So with the server you have eminlated the issue of a Graphical User Interface (GUI). Before anything you would have to get the
    PI 4 connected to the internet with the instructions in the |network| folder. This way you would want to install
    a VS Code Server that is using a localhost server. This would be in the |Server| folder.

Overall:

1. Get the Pi connected to the Internet
2. Install the ROS2 Humble Hawksbill
3. Install the camera software (Intel Realsense d435i)
    a. test by "realsense-viewer"
