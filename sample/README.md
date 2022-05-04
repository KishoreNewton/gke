docker build -t myapp .

docker run -d -p 8888:8888 myapp

docker tag myapp gcr.io/<your-project>/myapp

docker push gcr.io/<your-project>/myapp
