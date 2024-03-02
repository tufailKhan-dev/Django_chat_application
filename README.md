# Django chat application using websocket

This is a simple chat application built using Django, allowing users to engage in real-time communication via text messages.


## Installation

To run this application locally, follow these steps:

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/tufailKhan-dev/Django_chat_application.git
    ```

2. Navigate into the project directory:

    ```bash
    cd Django_chat_application
    ```

3. Create a virtual environment:

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
    source  env/bin/activate
    ```
    
5. Apply the database migrations:

    ```bash
    python manage.py migrate
    ```

6. Create a superuser (admin) account:

    ```bash
    python manage.py createsuperuser
    ```

7. Run the development server:

    ```bash
    python manage.py runserver
    ```

9. Access the application in your web browser at http://127.0.0.1:8000/chat.


## Technologies Used

- Django
- Django Channels (for WebSocket support)
- HTML/CSS
- JavaScript
- SQLite (for development)

## Contributing

Contributions are welcome! If you find any bugs or want to suggest improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
