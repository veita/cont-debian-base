# Debian Base System

Build a Debian base system container image.


## Run the image build

To build a Debian 11 Bullseye image run

```bash
./build-container.sh
```

To build an image with a specific Debian version
(`buster`, `bullseye`, `bookworm`) run

```bash
./build-container.sh buster
```

## Run the container

Run the container interactively.

```bash
podman run --name debian-base --hostname debian-base --rm -it localhost/debian-base-bullseye:latest
```


## Safety

Do not run `setup.sh` in your host system.

