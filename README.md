Cloud-Computing - 
Write a web application to find the weather of a given city

Task: Design the service using two microservices: 

- Zip Code

docker build -t zipcode-app
docker run -p 5001:5000 zipcode-app

- Weather

docker build -t weather-app
docker run -p 5002:5000 weather-app


Optional: Make these two microservices work together
python client.py
