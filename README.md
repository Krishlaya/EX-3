# EX-3

How to Run :
Build the Image

"docker build -t portfolio:multistage ."

Deploy the Container :
"docker run -d -p 8080:80 --name portfolio-final portfolio:multistage"
