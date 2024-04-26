# Use the official Python image from the Docker Hub
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install Flask
RUN pip install --no-cache-dir flask

# Expose the port on which the Flask app will run
EXPOSE 8000

# Command to run the Flask application
CMD ["python", "app.py"]
