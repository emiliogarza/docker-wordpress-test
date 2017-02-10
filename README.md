# Docker Wordpress Starter
Here's a simple starter compose.

Here's what you can do to make a localhost wordpress server setup.
1. Download Docker (https://www.docker.com/products/docker)
2. Put the yaml file in a directory.
3. Make some new directories at the same level of the yaml file for your theme
The path on the docker-compose file is currently: ./wp-content/themes, meaning 
Docker will pickup your themes you add into root/wp-content/themes and add them
to the Wordpress default themes.
4. In your terminal from the project root, run `docker-compose up` (show container logs) or `docker-compose up -d` (for no logs).  To stop the environment, press `ctrl+C` or run `docker-compose down`.
5. After it installs everything you can access your 5 minute Wordpress install page at: localhost:8080/