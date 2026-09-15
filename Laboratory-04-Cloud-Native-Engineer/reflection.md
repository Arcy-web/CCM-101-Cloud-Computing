### 1. How does the boot time and setup process of a Docker container compare to installing an operating system on a Virtual Machine?

The installation of the Docker container’s operating system is like faster than a Virtual Machines. The latter requires the installation of os before launching the application, unlike, with Docker, it is possible to run the required application without additional software by simply pulling the image and running it.

### 2. Why is port mapping (-p 8080:80) necessary when running a web server inside a container?

It is necessary to bind the port to a container to access the web-server, in this case, Nginx. The left side of the colon shows the host port, and the right side is the target port beside the container. Because of binding the 8080-th port of the host to the 80-th port of the container, it becomes possible to access Nginx through the http://localhost:8080 address.



### 3. What happens to the data inside a container when you use the docker rm command?

All the data stored in the container will be deleted as well. It means that the information that was only in the container, not in the external storage, will be deleted forever. In order not to lose an important data, it should be stored in an external source like  a Database.



### 4. How do you think containerization changes the way software developers and IT operations teams work together (DevOps)?

The tecxhinoly of containers made the creation of applications much easier and faster. It also made the interaction between developers and sysadmins much smoother. The application, its dependencies, and required data can be stored in the container. It means that one application can be launched both on the developer’s computer and a remote server, minimizing the differences beetwen the environments and saving time and effort.



### 5. How is your GitHub portfolio evolving?

My GitHub portfolio is growing solwly but steadily, as i am actively adding new laboratory activities and materials related to my research. Instead of just providing answers, i now also include research, docker commands, screenshots, and conclusions in my work. Each laboratory activity is now a complete work that shiows my knowledge and skills related to cloud technologies. The portfolio now serves me as a repository of my achievements that i can use to track progress and share my skills.

