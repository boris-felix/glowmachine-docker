To rebuild the image:

    docker build --force-rm=true --rm=true --tag="glow/postgresql:latest" .
    
To push the image:

    docker push glow/postgresql:latest

To run the service:

    fig up
