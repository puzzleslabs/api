# api

# Install [Homebrew](https://brew.sh)

```sh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

# Installing [Docker](https://www.docker.com)

```sh
brew install docker docker-machine docker-machine-driver-xhyve
```

# Create default Docker Machine

```sh
docker-machine create --driver xhyve default && docker-machine env default
```
