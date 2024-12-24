# Flask Application with Docker  

This repository demonstrates how to containerize a simple Flask application using Docker.  

## Files Overview  
- **`Dockerfile`**: Automates the environment setup and application execution.  
- **`app.py`**: Contains the Flask application code.  
- **`deepali.py`**: The entry point to run the Flask app.  

### Dockerfile Key Instructions  
- **`FROM`**: Specifies the base image (`redhat/ubi8`) for the container.  
- **`RUN`**: Installs Python and Flask.  
- **`WORKDIR`**: Sets the working directory inside the container.  
- **`COPY`**: Copies application files into the container.  
- **`CMD`**: Defines the command to run the application (`python3 deepali.py`).  
