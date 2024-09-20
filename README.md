Portfolio – 2024 Project
Overview
This project consists of a simple website developed using HTML, CSS, and JavaScript, showcasing information about me and some of my projects. The website is containerized using Docker to ensure consistent deployment across different environments.

The main tools used in this project are:

Docker Desktop: To manage containerization.
Visual Studio Code: As the primary code editor.
Git & GitHub: For version control and collaboration.
Netlify: For hosting and sharing the project.
Project Details
Creating a Docker Image and Running a Container
A Docker image was created using a Dockerfile that specifies the required environment and dependencies for the project. This ensures that the project can run consistently regardless of the host machine's configuration.

Steps to Create and Run the Docker Container:
Write the code for the project (HTML, CSS, JS).
Create a Dockerfile inside the project directory.
Specify the necessary instructions in the Dockerfile.
Build the Docker image using the terminal.
Run the image to start a Docker container.
Access the project locally by navigating to localhost:2000 in a web browser.
Git and GitHub Integration
Version Control and Collaboration: After completing the code, the project is pushed to GitHub to maintain version history and allow for collaboration.

Steps to Upload Code to GitHub:

Create a new GitHub repository.
Open the terminal in the project directory.
Initialize Git, add the project files, and push the code to the repository.
Deploying with Netlify
Netlify was used to host and share the project publicly. The platform automates the deployment process from GitHub, making it easy to deploy updates.

Steps to Deploy Using Netlify:
Register on Netlify using GitHub.
Add a new site.
Select the GitHub repository containing the project.
Set the site name and click deploy.
Share the generated link to make the project accessible to others.
This project serves as a demonstration of using modern DevOps tools like Docker and GitHub, combined with web technologies, to create, containerize, and deploy a personal portfolio site.
