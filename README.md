1. Create a file, add execution permissions
2. To create an image fom the file, create a Dockerfile that declares all of the required dependencies.
3. The file depends on something that can run shell scripts so we choose Alpine which is a Linx distro.
4. Use the docker build to turn the Dockerfile to an image.
5. Create a new file called additional.txt and copy it inside the container.