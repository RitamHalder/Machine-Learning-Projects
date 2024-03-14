# Django Polls App

The Django Polls App is a simple web application built with Django that allows users to create and participate in polls.

## Features

- Users can view a list of polls.
- Users can view the details of a specific poll.
- Users can vote on a poll.
- Admins can create new polls.
- Admins can view and manage existing polls.

## Technologies Used

- Python
- Django
- HTML
- CSS
- JavaScript

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/RitamHalder/Machine-Learning-Projects.git
    ```

2. Navigate to the project directory:

    ```bash
    cd myPollsite
    ```

3. Create a virtual environment (optional but recommended):

    ```bash
    python -m venv env
    ```

4. Activate the virtual environment:

    - On Windows:

        ```bash
        env\Scripts\activate
        ```

    - On macOS and Linux:

        ```bash
        source env/bin/activate
        ```

5. Install the project dependencies:

    ```bash
    pip install -r requirements.txt
    ```

6. Run the migrations to create the database schema:

    ```bash
    python manage.py migrate
    ```

7. Create a superuser to access the admin interface:

    ```bash
    python manage.py createsuperuser
    ```

8. Start the development server:

    ```bash
    python manage.py runserver
    ```

9. Open your web browser and navigate to `http://127.0.0.1:8000` to access the application.

## Usage

- To access the admin interface, go to `http://127.0.0.1:8000/admin` and log in with the superuser credentials created in step 7.
- From the admin interface, you can create, edit, and delete polls.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push the branch to your fork.
4. Submit a pull request with a description of your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

