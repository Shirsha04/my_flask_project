# Use Python base image
FROM python:3.10-slim

# Set the working directory
WORKDIR /app

# Copy files into the container
COPY . .

# Install required packages
RUN pip install -r requirements.txt

# Expose port 5000
EXPOSE 5000

# Run the app
CMD ["python", "app.py"]
