# Use Python:3.8.10 as base image
FROM python:3.8.10

# Set working directory
WORKDIR /app

# Copy requirements.txt to app directory
COPY ../requirements.txt ./

# Install packages 
RUN pip install --no-cache-dir -r requirements.txt

# Copy source code
COPY . .

# Expose port 5000
EXPOSE 8000

# Start the application
CMD ["uvicorn", "main:app", "--reload", "--host", "0.0.0.0", "--port", "8000"]