FROM php:8.1-apache

# Install MySQLi extension
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli

# Enable Apache mod_rewrite (optional, for frameworks like Laravel)
RUN a2enmod rewrite

# Set the working directory
WORKDIR /var/www/html

