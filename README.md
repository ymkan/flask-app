# flask-app
Storing Flask programs

Add new items

$ docker build -t <YOUR_USERNAME>/myfirstapp .
$ docker run -p 8888:5000 --name myfirstapp YOUR_USERNAME/myfirstapp
Head over to http://remotehost:8888 and your app should be live. 

Push image to Docker Cloud

docker login
docker push YOUR_USERNAME/myfirstapp
