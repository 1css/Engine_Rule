# Use the official Python image as a base
FROM python:3.9

# Set the working directory inside the container
WORKDIR /app

# Copy the requirements.txt file to the container
COPY requirements.txt ./

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Copy the entire rule_engine directory and manage.py to the container
COPY rule_engine/ ./rule_engine/
COPY rule_engine/manage.py ./

# Expose the port the app runs on
EXPOSE 5000

# Command to run the Django server
CMD ["python", "manage.py", "runserver", "0.0.0.0:5000"]
