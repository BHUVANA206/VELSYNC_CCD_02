Task 2: Dockerized Flask App
\\Description
          This project is a simple Flask app containerized using Docker. 
Features
Flask-based web server
Single endpoint (/) returning a greeting message
Containerized with Docker for easy deployment
How to Run Locally
Build the Docker image:
Copy code
Bash
docker build -t flask-task2 .
Run the Docker container:
Copy code
Bash
docker run -p 5000:5000 flask-task2
Open your browser at:
Copy code

http://localhost:5000
Screenshot
<img width="1483" height="762" alt="Screenshot 2025-12-30 094542" src="https://github.com/user-attachments/assets/6b561a22-7e0f-45f7-8a3a-8f476f7f95a8" />
<img width="1920" height="1020" alt="Screenshot 2025-12-30 094630" src="https://github.com/user-attachments/assets/f9a57ee1-7b07-4f16-bc1c-1b3c6e16dc46" />
