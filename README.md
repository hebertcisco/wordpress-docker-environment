# WordPress environment

[![Docker](https://github.com/hebertcisco/wordpress-docker-environment/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/hebertcisco/wordpress-docker-environment/actions/workflows/docker-publish.yml)
[![Docker Image CI](https://github.com/hebertcisco/wordpress-docker-environment/actions/workflows/docker-image.yml/badge.svg)](https://github.com/hebertcisco/wordpress-docker-environment/actions/workflows/docker-image.yml)

## Install Docker:

> See the link:
[https://docs.docker.com/get-docker/](https://docs.docker.com/get-docker/)

## Run localy:

> Run commands:

```
cd wordpress-docker-envioment
```

```
sudo docker-compose -f "docker-compose.yml" up -d --build
```
###  Install from the command line

```
docker pull ghcr.io/hebertcisco/wordpress-docker-environment:main
```
### Use as base image in Dockerfile:

```
FROM ghcr.io/hebertcisco/wordpress-docker-environment:main
```

> Open the link:
[localhost:8080](http://localhost:8080)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](issues).

## Show your support

Give a ⭐️ if this project helped you!

Or buy me a coffee 🙌🏾

<a href="https://www.buymeacoffee.com/hebertcisco">
    <img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=&slug=hebertcisco&button_colour=FFDD00&font_colour=000000&font_family=Inter&outline_colour=000000&coffee_colour=ffffff" />
</a>

## 📝 License

Copyright © 2023 [Hebert F Barros](https://github.com/hebertcisco).<br />
This project is [MIT](LICENSE) licensed.
