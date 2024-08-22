# WordPress Optimization Config

This repository contains a collection of configuration settings for optimizing WordPress performance through `php.ini` and `.htaccess` files. These settings can significantly enhance the speed and efficiency of your WordPress site.

## Contents

- `php.ini` – Settings to improve PHP performance and resource limits.
- `.htaccess` – Apache configuration settings to enable browser caching, Gzip compression, and more.

## `php.ini` Settings

The `php.ini` file includes settings to enhance PHP performance, such as:

- Increasing the memory limit to allow more resources for scripts.
- Extending the maximum execution time to handle longer processes.
- Configuring upload limits and post size limits for handling large files.
- Optimizing realpath cache size and TTL for better performance.
- Enabling opcode caching for faster script execution.

## `.htaccess` Settings

The `.htaccess` file contains Apache configurations for optimizing your site, including:

- **Browser Caching:** Configurations to instruct browsers to cache static resources, which reduces load times for returning visitors.
- **Gzip Compression:** Settings to enable Gzip compression, reducing the size of files sent from the server to the browser.
- **Leverage Browser Caching:** Additional configurations for leveraging browser caching for different types of resources.
- **Rewrite Rules:** Rules to manage URL rewriting, which can help in reducing HTTP requests and improving site performance.
- **Disable Directory Browsing:** Prevents users from seeing a list of files in directories without an index file.
- **Force HTTPS:** Configurations to redirect all HTTP requests to HTTPS for improved security.
