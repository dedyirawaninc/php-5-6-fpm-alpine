# php-5-6-fpm-alpine

Base image from php:5.6-fpm-alpine

# Create docker hub token for password and username

sudo nano ./docker/token/password.txt
sudo nano ./docker/token/username.txt

# Login into docker hub

./docker/login.sh

# Build to execute and upload develop branch

./docker/build/develop/execute.sh
./docker/build/develop/uplaod.sh

# Build to execute and upload main branch

./docker/build/main/execute.sh
./docker/build/main/uplaod.sh
