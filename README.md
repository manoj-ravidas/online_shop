1. vim Dockerfile

This command opens a Dockerfile in the vim text editor. A Dockerfile is a script that contains a series of commands to create a Docker image. You can specify base images, dependencies, configurations, and commands for the Docker container to run when started.

    Documentation:
        Dockerfile Reference
2. docker build -t online_shop .

This command builds a Docker image from the current directory (denoted by .) using the Dockerfile found there. The -t online_shop flag tags the image with the name online_shop, making it easier to reference.

    Documentation:
        docker build documentation

docker images

This command lists all Docker images stored locally on your machine, displaying the image repository, tag, image ID, creation time, and size.

    Documentation:
        docker images documentation

4. npm run dev

This command is used to run a development server defined in the scripts section of a Node.js project's package.json file. This is typically used to start a local server for testing or development purposes.

    Documentation:
        npm run documentation

5. docker ps

This command lists all currently running Docker containers. It displays the container ID, image, command, creation time, status, ports, and names of the running containers.

docker run -d -p 3000:5173 --name online-shopping online_shop

This command runs a Docker container based on the online_shop image:

    -d: Runs the container in detached mode (in the background).

    -p 3000:5173: Maps port 5173 in the container to port 3000 on the host, allowing you to access the app via port 3000.

    --name online-shopping: Names the container online-shopping.

    online_shop: Specifies the image to use for the container.

7. http://192.168.2.78:3000/

This is a URL to access the application running in the Docker container. The container is mapped to the host's port 3000, so you can access it by visiting this URL in your web browser. The IP address 192.168.2.78 is likely the local network address of your machine.
