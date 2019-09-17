<h2>coincube-back</h2>
This repo contains the Coincube Flask Web Application API.

<h3>Getting Started</h3>
In order to get up and running with this repo:

<h3>Docker Setup</h3>
You will need <a href="https://docker.com" target="_blank">Docker</a>.

<h3> Database Submodule</h3>
This repo uses one submodule which you will need to pull in:
`git submodule init` <br>
`git submodule update` <br>

<h3>Troubleshooting</h3>
Make sure that old docker networks are removed<br>
'docker-compose down' should remove them<br>
Check with 'docker network ls'<br>
If you see errors related to Disk Space, you may need to reset Docker:<br>
To do so: Docker -> Preferences -> Reset -> Remove All Data