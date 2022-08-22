# this is my docker Example project

## to build and image
docker build -t 'bocacode':1.0 .

## to create a cointainer
docker run --rm -d -p 8000:8000/tcp bocacode:1.0