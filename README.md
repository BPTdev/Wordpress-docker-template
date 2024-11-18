# WordPress Docker Template

This repository contains a customizable WordPress Docker template for quickly deploying and managing WordPress sites. It includes a pre-configured Docker environment and options to add themes, plugins, and custom configurations.

## Features

- **Dockerized WordPress**: Leverages the official WordPress Docker image for easy deployment.
- **Customizable Configuration**: Add your own themes, plugins, and configurations effortlessly.
- **Lightweight Repository**: The template excludes WordPress core files, making it easy to maintain and update.
- **Pre-configured Volumes**: Persistent storage for WordPress files and database.

## Folder Structure

```plaintext
├── docker-compose.yml    # Docker Compose configuration
├── Dockerfile            # Custom Dockerfile to build your environment
├── wp-config/            # Contains custom wp-config.php and other configuration files
├── themes/               # Your custom WordPress themes
├── plugins/              # Your custom WordPress plugins
└── scripts/              # Additional scripts (e.g., widgets.js)
