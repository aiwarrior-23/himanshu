# Titanic Data API with Falcon
This project provides a simple API to interact with the Titanic dataset using the Falcon web framework. It exposes two endpoints: one to fetch the first n records, and another to fetch information about a passenger by their passenger ID.

# Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

# Prerequisites
You need to have Python installed on your machine. This project uses the Falcon web framework and pandas for data manipulation. You can install them with pip:
```python
pip install falcon gunicorn pandas
```
You will also need the Titanic dataset in a CSV file. Place the 'titanic.csv' file in the same directory as the script.

# Running the API
To run the API, use a WSGI server such as wsgiref.simple_server. If your script is named app.py, you can start the server with:
```python
python app.py
```

# Endpoints
***/first/{n}***: Fetch the first n records from the Titanic dataset. Replace {n} with the desired number of records.

***/passenger/{passenger_id}***: Fetch information about a passenger by their passenger ID. Replace {passenger_id} with the desired passenger ID.

# Built With
Falcon - The web framework used
pandas - Data manipulation and analysis library

# License
This project is licensed under the MIT License
