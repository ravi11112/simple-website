# simple-website
in this project we wiil create a Dockerfile file for a simple html application and create its image and access it from internet.


# creating image from dockerfile ( . this present in current directory )
docker build -t <image> .

# allow port 8000 
docker run -d -p 8000:80 <image>



