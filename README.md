# College Reuse

College Reuse is a platform designed to facilitate the buying and selling of second-hand college materials among students. This project was developed as a mini project for the SYCOMPS 2024 course.

## About the Project

College Reuse is a web-based application that allows students to buy and sell used college materials such as textbooks, lab equipment, and other study resources. The platform aims to promote sustainability and affordability within the student community.

## Features

- **User Registration and Login**: Users can create accounts and log in to access the platform's features.
- **Product Listings**: Users can list their items for sale, including images and descriptions.
- **Catalog Browsing**: Browse through available items listed by other users.
- **User Dashboard**: Manage your listed products and view your account details.

## Getting Started

Follow these steps to set up the project locally.

### Prerequisites

Ensure you have the following installed:

- A web server with PHP support (e.g., XAMPP, WAMP)
- MySQL or a compatible database system
- A code editor (e.g., VS Code, Sublime Text)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sanikapendurkar/College-Reuse.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd College-Reuse
   ```
  
3. **Set up the database**:
   - Create a new MySQL database.
   - Import the provided SQL file (database.sql) to set up the necessary tables.
  

4. **Configure the database connection**:
   - Open dbh.inc.php in a code editor.
   - Update the database credentials (servername, username, password, dbname) to match your local setup.
  

5. **Start the web server**:
   - Ensure your web server is running and has access to the project directory.
  

6. **Access the application**:
   - Open a web browser and navigate to http://localhost/College-Reuse/home.php.
  
## Usage

- **Home Page**: Access home.php to browse available study materials.
- **User Registration**: Use register.php to create a new account.
- **User Login**: Access login.php to log in to your account.
- **Add Product**: After logging in, use yourpdt.php to list a new study material for sale.
- **Logout**: Use logout.php to end your session.
  
