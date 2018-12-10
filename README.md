# clustalo-docker
Docker image running Ubuntu 16.04 with clustalo 1.2.4 installed.

Run:
```bash
docker run -it -v $(pwd):/in/ -w /in/ --rm chrishah/clustalo-docker:1.2.4 clustalo --help
```

