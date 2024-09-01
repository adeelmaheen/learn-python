# Use the official Python image from the Docker Hub
FROM python:3.9-slim

# Install Jupyter
RUN pip install 

# Set the working directory in the container
WORKDIR /usr/src/app

COPY . .

# Expose the Jupyter port
EXPOSE 8888

# Command to run Jupyter Notebook
CMD ["jupyter", "notebook", "--ip=0.0.0.0", "--port=8888" ,"--allow-root", "--no-browser"]
