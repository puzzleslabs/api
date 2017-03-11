# api

# Install [Homebrew](https://brew.sh)

```sh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

# Installing [Docker](https://www.docker.com)

```sh
brew install docker docker-machine docker-machine-driver-xhyve docker-compose
```

# Create default Docker Machine

```sh
docker-machine create --driver xhyve --xhyve-experimental-nfs-share default
```

# Add to `.bashrc` or `.zshrc` or `.fishconfig`

```sh
docker-machine start default

// for bash & zhs
eval $(docker-machine env default)

// for fish
eval (docker-machine env default)
 ```
