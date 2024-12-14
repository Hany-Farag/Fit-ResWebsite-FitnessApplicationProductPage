## Fit-Res Website - Fitness Application Product Page (Undergraduate Project)

During the COVID-19 pandemic, maintaining physical fitness became a major challenge due to restrictions on gyms and outdoor activities. To address this issue:
#### The Fit-Res project was developed as a comprehensive solution to promote fitness and well-being through mobile applications available on Android and iOS devices.

### The Fit-Res website serves as a product page showcasing the app's features while also offering a dynamic Articles Section to provide fitness tips, workout guides, and health-related content.

## My Contribution:
- Create the website design
- Designed and implemented a simple admin dashboard to manage website content efficiently.
- Developed core functionalities(CRUD) for the Articles Section
## Technologies Used:
- ##### Backend: Laravel, MySQL
- ##### Frontend: HTML, CSS, JavaScript
- ##### Version Control: Git
##
![screencapture-127-0-0-1-8000-2024-12-14-17_33_](https://github.com/user-attachments/assets/a0bbb714-9d40-4c80-bba3-8005588d19d0)

## How to run project locally
Follow these steps to set up and run the project on your local machine:

### - Clone the Repository
    Use git to clone the project to your local machine: git clone https://github.com/yourusername/repository-name.git
    
### - Install Dependencies
Make sure Composer is installed, then run:
bash : composer install

### - Set Up Environment Configuration
Duplicate the .env.example file and rename it to .env:
bash: cp .env.example .env

### - Update the .env file with your database and app configurations:

### - Run the following command to set the application encryption key:
bash: php artisan key:generate
### - Create a new database named as defined in the .env file:
sql: CREATE DATABASE your_database_name;
### - Run database migrations to create the required tables:
bash: php artisan migrate

### - Start the Laravel development server:
bash:php artisan serve
### - Open your browser and visit:
http://127.0.0.1:8000.


### Requirements
##### Ensure the following are installed on your machine:PHP >= 8.x | Composer | MySQL



