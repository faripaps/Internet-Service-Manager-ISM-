# Internet Service Manager (ISM)

## Overview
The Internet Service Manager (ISM) is a PHP-based platform that allows users to purchase data packages using a token-based system. This application provides a user-friendly interface for managing internet usage, tracking data consumption in real-time, and ensuring a seamless purchasing experience.

## Features
- **Token Purchase System**: Users can buy data packages ranging from 500 MB to 2 GB, with clear pricing and validity periods.
- **Real-Time Usage Tracking**: Monitor current data usage and remaining balance through an intuitive dashboard.
- **RESTful API**: Interaction with the data and user accounts is facilitated via a REST API.
- **Notifications**: Receive alerts when nearing data limits and notifications upon exhaustion.
- **User-Friendly Interface**: Simple navigation for purchasing tokens, tracking data, and managing accounts.

## Technologies Used
- **Backend**: PHP
- **Package Manager**: Composer
- **Database**: MySQL
- **APIs**: RESTful API for data communication

## Getting Started

### Prerequisites
- PHP (v7.4 or later)
- Composer
- MySQL
- Web Server (e.g., Apache or Nginx)

### Installation Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/ism.git
Navigate to the project directory:

bash

cd ism
Install dependencies using Composer:

bash

composer install
Set up the database:

Create a database in MySQL.
Import the provided SQL schema (e.g., schema.sql) to set up the necessary tables.
Configuration:

Rename the config.sample.php file to config.php and update database credentials and any other necessary settings.
Start the web server:

If using PHP's built-in server:
bash

php -S localhost:8000
For Apache or Nginx, configure the server to point to the project directory.
Access the application:

Open your web browser and navigate to http://localhost:8000 (or your server's address).
-API Endpoints
-GET /api/data: Retrieve available data packages.
-POST /api/purchase: Purchase tokens for selected data packages.
-GET /api/usage: Get current data usage and remaining balance.
   
   # Contributing
We welcome contributions from the community! Please see the CONTRIBUTING.md file for guidelines on how to contribute.

# License
This project is licensed under the MIT License.

# Contact
For any questions or feedback, please contact georgepapaya@gmail.com.
