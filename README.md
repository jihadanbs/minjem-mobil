# 💰 HutangMU - Debt Management System

HutangMU is a simple web-based application designed to help users manage debts. With this system, users can record and track debts, set reminders, and view the status of repayments. The application aims to simplify debt management for individuals or small businesses.

## 📋 Features

- **Debt Recording**: Easily record who owes you money or track debts you owe to others.
- **Debt Reminders**: Set reminders to ensure timely repayments.
- **Payment Status**: Track payment history and check the status of repayments.
- **Simple Dashboard**: View a summary of all active debts and payments due.
- **Search and Filter**: Find specific debts based on status, amount, or debtor information.

## 🚀 How to Use

1. **Clone the Repository**

    To start using the system, clone this repository to your local machine:

    ```bash
    # Clone this repository
    $ git clone https://github.com/jihadanbs/HutangMU

    # Navigate to the repository
    $ cd HutangMU

    # Open the project in your preferred text editor
    $ code .
    ```

2. **Install Dependencies**

    Make sure you have PHP, Composer, and a database such as MySQL installed. Then, install the dependencies by running:

    ```bash
    composer install
    ```

3. **Setup the Database**

    - Create a new MySQL database for this project.
    - Copy `.env.example` to `.env` and update the database credentials in the `.env` file:

    ```bash
    DB_DATABASE=your_database_name
    DB_USERNAME=your_username
    DB_PASSWORD=your_password
    ```

4. **Run Database Migrations**

    Migrate the database tables with the following command:

    ```bash
    php artisan migrate
    ```

5. **Run the Application**

    Start the local development server:

    ```bash
    php artisan serve
    ```

    Your application will now be accessible at `http://localhost:8000`.

## 🖥️ Deployment

To deploy HutangMU online, you can follow one of these methods:

- **Heroku**: Deploy using [Heroku](https://devcenter.heroku.com/articles/getting-started-with-php).
- **VPS/Shared Hosting**: Upload the project to your server that supports PHP and MySQL. Configure your environment variables and run migrations on the server.

## 📝 Contributing

Contributions are welcome! If you want to add new features or fix bugs, you can contribute by following these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to your branch (`git push origin feature-branch`).
5. Submit a pull request.

## 🛠️ Technologies Used

- **PHP**: Backend scripting language.
- **Laravel**: Web application framework.
- **MySQL**: Relational database management.
- **JavaScript**: Frontend scripting.
- **HTML/CSS**: Frontend design.

## 🏗️ Future Features

- **Notification System**: Integrate email or SMS notifications for upcoming due payments.
- **User Roles**: Implement user roles for different types of access (e.g., admin, user).
- **Multi-Currency Support**: Add support for recording debts in multiple currencies.

## 🤝 License

This project is licensed under the [MIT License](LICENSE).

---

**Connect with me**:

- GitHub: [@jihadanbs](https://github.com/jihadanbs)
- YouTube: [@jihadanbs](https://www.youtube.com/@jihadanbeckhiano3044)
- Instagram: [@jihadanbs](https://instagram.com/jihadanbs/)
- LinkedIn: [@jihadanbs](https://www.linkedin.com/in/jihadan-beckhianosyuhada-68b977277/)
