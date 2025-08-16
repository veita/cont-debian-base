# Debian Base System

Build a Debian base system container image.


## Run the image build

To build a Debian 13 Trixie image run

```bash
./build-container.sh
```

To build an image with a specific Debian version
(`bullseye`, `bookworm`, `trixie`, `forky`) run

```bash
./build-container.sh bookworm
```

## Run the container

Run the container interactively.

```bash
podman run --name debian-base --hostname debian-base --rm -it localhost/debian-base-trixie:latest
```


## Safety

Do not run `setup.sh` in your host system.

