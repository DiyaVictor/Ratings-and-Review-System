# Ratings and Review System

A web-based platform designed to facilitate user-generated reviews and ratings for various products or services. This system enables users to register, authenticate, and share their feedback, fostering a community-driven environment for quality assessments.

## Features

- *User Authentication*: Secure registration and login functionalities to manage user sessions.
- *Review Management*: Users can add, update, and view reviews for different products or services.
- *Structured Data Storage*: Utilizes a relational database to store user information and reviews efficiently.
- *Modular Codebase*: Organized into components for scalability and maintainability.

## Project Structure


├── components/           # Reusable PHP components
├── css/                  # Stylesheets for UI design
├── js/                   # JavaScript files for interactivity
├── uploaded_files/       # Directory for uploaded content
├── add_review.php        # Page to submit new reviews
├── all_posts.php         # Displays all reviews
├── login.php             # User login page
├── register.php          # User registration page
├── update.php            # Update user information
├── update_review.php     # Edit existing reviews
├── view_post.php         # Detailed view of a single review
├── reviews_db.sql        # SQL script to set up the database
└── README.md             # Project documentation


## Getting Started

### Prerequisites

- PHP 7.x or higher
- MySQL 5.x or higher
- Web server (e.g., Apache, Nginx)

### Installation

1. *Clone the Repository*:
   bash
   git clone https://github.com/DiyaVictor/Ratings-and-Review-System.git
   

2. *Set Up the Database*:
   - Create a new MySQL database.
   - Import the reviews_db.sql file to set up the necessary tables.

3. *Configure Database Connection*:
   - Update the database connection settings in the PHP files (e.g., components/db_connect.php) with your database credentials.

4. *Deploy to Web Server*:
   - Place the project files in your web server's root directory.
   - Ensure the server has the necessary permissions to access the files.

5. *Access the Application*:
   - Navigate to http://localhost/Ratings-and-Review-System/ in your web browser.

## Usage

- *Register*: Create a new user account via the registration page.
- *Login*: Access your account using your credentials.
- *Add Review*: Submit a new review for a product or service.
- *View Reviews*: Browse all submitted reviews.
- *Edit Review*: Modify your existing reviews.

## Acknowledgments

Developed by [Diya Victor](https://github.com/DiyaVictor) to address the growing need for a comprehensive platform where users can provide feedback and reviews for various products or services.
![image](https://github.com/user-attachments/assets/5d7cda92-317c-4e4e-87ba-6c866dc9839b)
![image](https://github.com/user-attachments/assets/bb63d191-b397-427a-a20a-fc0d8d38fa39)
![image](https://github.com/user-attachments/assets/05d2126d-6647-4018-9568-762d9a9bd086)
![image](https://github.com/user-attachments/assets/cb4f83fc-3e06-405e-b747-003a96124acb)
![image](https://github.com/user-attachments/assets/d2094c85-69a0-408f-987f-cdc2d3c3ad35)
![image](https://github.com/user-attachments/assets/ff1046b1-80df-4c1b-a05a-27b2536ea05a)
