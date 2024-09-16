FROM python:3.11-slim-buster

# Set the working directory
WORKDIR /app


# Copy the Python script to the container
COPY palindromechecker.py /app/

COPY requirements.txt /app/

# Install required dependencies
RUN  pip install --upgrade pip && pip install -r requirements.txt




# Expose the port (optional, if you want to expose a port)
EXPOSE 8080

# Define the entry point
CMD ["python", "palindromechecker.py"]          
