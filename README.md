# Turtlesim-package-in-ROS-noetic


1- First you need to install Turtlesim
```
sudo apt install ros-noetic-desktop-full
```

![image](https://github.com/user-attachments/assets/6bf5f170-476e-4b9b-85b2-67c3ab5082fc)







If you encounter any problems, just follow the following:
s1-Make sure your package list is up to date by running the following commands: ```   sudo apt update
sudo apt upgrade```

s2-``` sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list' ```

s3-    ```sudo apt install curl```
       
s4     ```curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add -```
       
s5-  ```sudo apt install ros-noetic-desktop-full```



2- Configuring the ROS environment:
Make sure your ROS environment is set up correctly by adding the following line to your .bashrc file:

```    echo "source /opt/ros/noetic/setup.bash" >> ~/.bashrc ```
``` source ~/.bashrc      ```


3- using ```rosecore```, you will see this:

![image](https://github.com/user-attachments/assets/2c59c79e-b235-459f-b6d6-60f7af3aa893)



4-Open a new window and type the command ```rosrun turtlesim turtlesim_node```

The turtle page will appear.

![image](https://github.com/user-attachments/assets/0f3f1801-8fec-4ce4-be87-bb768c1b6ccc)



5- Open a new window and type the third command ```  rosrun turtlesim turtle_teleop_key   ```


![image](https://github.com/user-attachments/assets/b814f739-8916-4b86-bfbf-342c56e9569a)


Now you can control the turtle using the arrows.

![image](https://github.com/user-attachments/assets/8c97fc61-c68e-49b2-ba1b-6f89dafeb9f8)








