# drun
Alias to run the Docker container in the current directory with user UID/GID

# Usage

> drun \[OPTIONS\] IMAGE \[COMMAND\] \[ARG...\]

See 'docker run --help'.

## Examples

```bash

git clone https://github.com/denel-manilov/drun.git

cd drun/examples

drun php:7-cli php hello.php

drun node:8 node cat.js

```

# Installation

```bash

curl -L "https://raw.githubusercontent.com/denel-manilov/drun/master/drun.sh" -o ~/.local/bin/drun

chmod +x ~/.local/bin/drun

```
# Requirements

> [Docker](https://docs.docker.com/ "Docker")
