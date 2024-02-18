# Base image
FROM python:3.8

# Set working directory
WORKDIR /app

# Copy file to install dependencies
COPY requirements.txt .

# Install dependencies
RUN pip install -r requirements.txt

# Copy application code to container
COPY . .

# Expose port
EXPOSE 5001

# Set envireonment variables
# ENV envname = value

# Run the app at the container start
CMD ["python", "app.py"]