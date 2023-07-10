# Online Judge Platform
This project is a django-based online judge platform that remotely compiles user submitted code for a programming problem.It provides an efficient and reliable solution for running and evaluating code submissions.

## Features
* **Code Compilation**: Users can submit their code solutions to programming problems, which are remotely compiled and executed.
* **Problem Statements**: The platform provides problem statements for various programming problems that users can solve.
* **Efficient Storage**: PostgreSQL is used as the backend database to ensure optimal performance and data integrity.
* **Code Evaluation**: The platform evaluates the submitted code solutions.
* **Leaderboard**: A leaderboard is implemented to keep track of the most recent solutions.
* **User Authentication**: Users can create accounts and log in to the platform to access additional features such as submitting code and tracking their progress.

## Technologies Used
* **Django**: The web framework used for building the platform.
* **PostgreSQL**: The backend database for efficient storage and retrieval of problem statements, code submissions, and leaderboard.
* **HTML/CSS**: The front-end languages used for designing the user interface.
* **JavaScript**: Used for enhancing the user experience and implementing interactive features.

## You can access the website using : [Link](https://oj-project-6knd.vercel.app/judge/)

## Installation
To run the Django Online Judge Platform locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/online-judge-platform.git

2. Change into the project directory:
   ```bash
   cd online-judge-platform

3. Create a virtual environment:
   ```bash
   python3 -m venv venv

4. Activate the virtual environment:
   ```bash
   source venv/bin/activate

5. Install the dependencies:
   ```bash
   pip install -r requirements.txt

6. Set up the PostgreSQL database. Make sure you have PostgreSQL installed and running on your machine. Create a new database and update the database configuration in the settings.py file.
7. Apply the database migrations:
   ```bash
   python manage.py migrate

8. Start the development server:
   ```bash
   python manage.py runserver

9. Access the platform in your web browser at http://localhost:8000.


## Contributing

Contributions to the Django Online Judge Platform are always welcome! If you have any suggestions, bug reports, or feature requests, please open an issue on the GitHub repository. You can also fork the repository, make changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contact

If you have any questions or need assistance, feel free to reach out to the project maintainers:

- Anshika Bhatt: anshikabhatt0207@gmail.com


