How to run
    Install Docker
    docker-compose build
    docker-compose up
    Open OBS and in settings set the server to rtmp://localhost:1935/live and the stream key to abdi?key=supersecret
    Open VLC and Open a Network Stream and set the url to rtmp://localhost:1935/live/abdi
    You should see your live stream now!
