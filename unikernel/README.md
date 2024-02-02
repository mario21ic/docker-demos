Install:
```
brew install unikraft/cli/kraftkit
```

On macOS:
```
docker run --rm -d --name buildkit --privileged moby/buildkit:latest
export KRAFTKIT_BUILDKIT_HOST=docker-container://buildkit
```

Running:
```
kraft run -p 8080:8080 .

kraft ps
kraft net ls

curl localhost:8080
```
