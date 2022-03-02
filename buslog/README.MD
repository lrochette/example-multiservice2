## Flaskr an example application written in Python/Flask

![Flask plus Codefresh](docker-flask-codefresh.jpg)

Original source code from https://github.com/pallets/flask/tree/master/examples/tutorial

## Docker instructions

To create a docker image execute: 

`docker build . -t flaskr`

To run the docker image execute:

`docker run -p 5000:5000 flaskr` and visit with your browser http://localhost:5000

To run unit tests inside the container execute:

`docker run -it flaskr /bin/sh`

and then in the new command promt run

`pip install pytest && pytest`
Adding line Tue Mar  1 09:54:45 MST 2022
Adding line Tue Mar  1 14:56:40 MST 2022
Adding line Tue Mar  1 16:45:31 MST 2022
Adding line Tue Mar  1 17:05:25 MST 2022
Adding line Tue Mar  1 17:08:11 MST 2022
Adding line Wed Mar  2 14:18:37 MST 2022
