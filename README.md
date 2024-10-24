# 🚗 Minjem Mobil - Car Rental Management System

Minjem Mobil is a web-based application designed to help manage car rental operations. The system provides a platform for both car rental companies and customers to easily manage bookings, track rental availability, and manage transactions.

## 📋 Features

- **Car Management**: Add, update, or remove available cars for rent.
- **Rental Bookings**: Customers can book available cars for specific dates.
- **Transaction Management**: Track rental payments and outstanding balances.
- **Rental History**: View past and current rentals for each customer.
- **User Authentication**: Secure login system for both customers and admins.
- **Dashboard**: Admin dashboard for managing all rental operations in one place.

## 🚀 How to Use

1. **Clone the Repository**

    To begin using the system, clone the repository to your local machine:

    ```bash
    # Clone this repository
    $ git clone https://github.com/jihadanbs/minjem-mobil

    # Navigate to the repository directory
    $ cd minjem-mobil

    # Open the project in your preferred text editor
    $ code .
    ```

2. **Install Dependencies**

    Ensure you have PHP, Composer, and MySQL installed on your system. Then, install the required dependencies:

    ```bash
    composer install
    ```

3. **Set Up the Database**

    - Create a new MySQL database for the project.
    - Copy `.env.example` to `.env` and update the database credentials in the `.env` file:

    ```bash
    DB_DATABASE=your_database_name
    DB_USERNAME=your_username
    DB_PASSWORD=your_password
    ```

4. **Run Database Migrations**

    Set up the database by running the migrations:

    ```bash
    php artisan migrate
    ```

5. **Seed the Database (Optional)**

    You can seed the database with some initial data using the following command:

    ```bash
    php artisan db:seed
    ```

6. **Run the Application**

    Start the local development server:

    ```bash
    php artisan serve
    ```

    The application will be available at `http://localhost:8000`.

## 🖥️ Deployment

To deploy Minjem Mobil to the web, you can use:

- **Heroku**: Refer to the [Heroku documentation](https://devcenter.heroku.com/articles/getting-started-with-php) for deploying PHP applications.
- **VPS/Shared Hosting**: Upload the project files to your server, ensure PHP and MySQL are set up, and configure the `.env` file accordingly.

## 📝 Contributing

If you wish to contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-branch`).
3. Make the necessary changes and commit them (`git commit -am 'Add new feature'`).
4. Push the branch to your forked repository (`git push origin feature-branch`).
5. Submit a pull request for review.

## 🛠️ Technologies Used

- **PHP**: Backend scripting language.
- **Laravel**: Web application framework.
- **MySQL**: Relational database for storing data.
- **JavaScript**: Frontend scripting.
- **HTML/CSS**: User interface and design.
- **Composer**: Dependency management for PHP.

## 🏗️ Future Features

- **Multi-Language Support**: Allow the platform to support multiple languages.
- **Car Availability Calendar**: Visual calendar to track car availability.
- **SMS/Email Notifications**: Send automatic notifications for booking confirmations or reminders.
- **Mobile App**: Integrate the platform with a mobile app for easy access.

## 🤝 License

This project is licensed under the [MIT License](LICENSE).

---

**Connect with me**:

- GitHub: [@jihadanbs](https://github.com/jihadanbs)
- YouTube: [@jihadanbs](https://www.youtube.com/@jihadanbeckhiano3044)
- Instagram: [@jihadanbs](https://instagram.com/jihadanbs/)
- LinkedIn: [@jihadanbs](https://www.linkedin.com/in/jihadan-beckhianosyuhada-68b977277/)
