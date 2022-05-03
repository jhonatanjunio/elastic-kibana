# Logs and Observability - Elastic Stack (Elastic Search + Kibana + Beats)

Manage your application logs in a simple "dockerized" way using the Elastic Stack!
In this project we are using a nginx server.

How to use this project? After cloning it, do the following:

- `docker-compose up -d`

- `cd nginx`

- `docker build -t yourimagename/nginx-beats .`

Then, at the nginx dir do `docker-compose up -d --build` and your nginx is available at your `http://localhost:9000` !
Check your `http://localhost:5601`, where your Kibana should be running.

Enjoy! <br/><br/>

##### Made with 💜 by [Jhonatan](https://github.com/jhonatanjunio) and [Claudio](https://github.com/claudioemmanuel)
