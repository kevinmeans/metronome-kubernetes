# metronome-kubernetes
Metronome Takehome

To create the backend for the metronome project, run create_backend.sh.  To delete the kubernetes resources, run delete_backend.sh.  Running the create script will create a mysql server and a NodeJS webserver.  The NodeJS webserver will interact with the mysql server.  The nodejs server will use an image that is built from the metronome-nodejs project repo.  Specifically it will pull https://hub.docker.com/r/kevmeans/metronome-node-app.  Running this requires a working kubernetes cluster accessible via kubectl.
