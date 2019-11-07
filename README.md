# hello world

The hello world image demonstrates the last step in leveraging the Python Docker image hierarchy demonstration. It uses the Flask image (<https://github.com/relenteny/flask>) to build the Hello World example from the Flask Mega Tutorial (<https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world>).

Available in Docker Hub, the image can be invoke using ```docker run -it -p 5000:5000 relenteny/flask-helloworld:1.0.0```. This will instantiate a container and make the web gateway available at port 5000. By default, the URLs available will be <http://localhost:5000> and <http://localhost:5000/index>. This assumes that Docker is available at ```localhost``` (which would be the default case when using Docker for Mac or Docker for Windows). Depending on Docker installation configuration, the host name may be different.
