![Logo](Logo.png)
# Present Monitor

Present Monitor is a web-based service designed to automate the process of checking and sending daily attendance records for students and teachers. Built with Next.js and PostgreSQL, it ensures users receive their attendance information without the need to manually log in each day.

## Features

- **Automated Attendance Retrieval**: Logs into the college attendance website using user credentials to capture attendance data.
- **Daily Notifications**: Sends daily attendance updates via email and WhatsApp.
- **User-Friendly Interface**: Easy-to-use interface for entering and managing user credentials.
- **Secure Data Handling**: Ensures the security of user credentials and attendance data.

## Technology Stack

- **Frontend**: Next.js
- **Backend**: Node.js
- **Database**: PostgreSQL

## Setup and Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/VyomOp2/Present-Monitor.git
    cd Present-Monitor
    ```

2. **Install dependencies**:
    ```sh
    npm install
    ```

3. **Set up the database**:
    - Ensure PostgreSQL is installed and running.
    - Create a new database and update the database configuration in `config/database.js`.

4. **Run the application**:
    ```sh
    npm run dev
    ```

5. **Environment Variables**:
    - Create a `.env` file in the root directory.
    - Add the necessary environment variables as shown in `.env.example`.

## Usage

1. **Sign Up**: Users can sign up by providing their email, WhatsApp number, username, and password for the college attendance website.
2. **Daily Notifications**: Once signed up, users will receive daily attendance updates via email and WhatsApp.

## Contributing

We welcome contributions! Please read our [Contributing Guidelines](CONTRIBUTING.md) before submitting a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or issues, please contact us at [support@presentmonitor.com](mailto:support@presentmonitor.com).

---

*This project is developed and maintained by Vyom Maloo.*
