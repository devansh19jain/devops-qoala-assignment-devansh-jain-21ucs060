# Use the official Python 3.9 image from Docker Hub
FROM python:3.9

# Set the working directory inside the container (fixed typo from "appp" to "app")
WORKDIR /app  

# Copy the application file to the working directory (fixed typo from "appy.py" to "app.py")
COPY app.py /app

# Install required Python packages (corrected package name from "netiface" to "netifaces")
RUN pip install flask netifaces

# Expose port 8000 for the application (changed "eight thousand" to numeric 8000)
EXPOSE 8000 

# Start the Python application (fixed typo in CMD from "pythn" to "python")
CMD ["python", "app.py"]













