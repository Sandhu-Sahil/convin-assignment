# Convin Assignment By Sahilsher Singh

This is a backend project that provides two APIs for initializing the signup with Google and getting access to the calendar data related to that Google account. It also provides an API to show the calendar events data that is fetched from the signup email.

## API endpoints

The project provides the following two API endpoints:

1. `/rest/v1/calendar/init`: This endpoint is used for initializing the signup with Google and getting access to the calendar data related to that Google account.

2. `/rest/v1/calendar/redirect`: This endpoint is used to show the calendar events data that is fetched from the signup email.

## Setup

Follow the instructions below to set up and run the project:

1. Create a virtual environment using the following command:

    ```
    python3 -m venv env
    ```

2. Activate the virtual environment using the following command:

    ```
    source env/bin/activate
    ```


3. Install the required packages by running the following command:

    ```
    pip install -r requirements.txt
    ```


4. Run database migrations using the following command:

    ```
    python3 manage.py migrate
    ```


5. Start the development server using the following command:

    ```
    python3 manage.py runserver
    ```

The project should now be running on http://localhost:8000/
