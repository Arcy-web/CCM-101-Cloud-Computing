## Container Lifecycle Commands

### 1. Running Containers
```bash
docker ps
```
This command shows all currently running Docker containers and displays information like the container ID, image, status, and ports.

### 2. Stop the Running Container

```bash
docker stop nginx-server
```

This command stops the running Nginx container named `nginx-server`.

### 3. Verify the Container is Stopped

```bash
docker ps
```
This command verifies that the Nginx container is no longer running.

To view both running and stopped containers, the following command can also be used:
```bash
docker ps -a
```
### 4. Remove the Container Completely

```bash
docker rm nginx-server
```
This command deletes the stopped `nginx-server` container from the Docker environment.

### This is the Screenshot of output 

<img width="1920" height="1020" alt="Screenshot 2026-09-15 124118" src="https://github.com/user-attachments/assets/45b3b361-d384-43d0-8bb9-a1f214ff7fc4" />

## Lifecycle conclusion

The Docker container lifecycle starts by running a container, checking its status, stopping it when it is no longer needed, and finally removing it completely.


