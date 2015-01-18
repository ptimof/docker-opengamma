# ptimof/docker-opengamma

Docker container for the [OpenGamma](https://github.com/OpenGamma/OG-Platform/) demo.

## Quickstart

	docker build -t ptimof/opengamma .
	docker run --rm -p 8080:8080 ptimof/opengamma

Wait for the server to start up (should a minute or so), then point your browser to `http://localhost:8080`
