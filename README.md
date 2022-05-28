# Pull the repo
git clone https://github.com/bryon-czoch/Wordpress-With-Docker.git

# Build the image
docker build Wordpress-With-Docker/dockerfiles/wordpress

# Change directory to the docker yml file
cd Wordpress-With-Docker/wp_final/

# Run teh codes
docker-compose up

# Profit
