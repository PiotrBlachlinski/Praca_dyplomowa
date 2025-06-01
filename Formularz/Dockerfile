FROM python:3.13

WORKDIR /app
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
COPY . .
EXPOSE 5000
CMD ["python", "main.py"]
# This Dockerfile sets up a Python environment, installs dependencies from requirements.txt,
# copies the application code into the container, and runs the application using main.py.    