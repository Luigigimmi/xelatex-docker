# Xelatex Docker
Docker image with everything to build latex PDFs

## How to download it

Pull the image from the GitHub docker registry

```
docker pull ghcr.io/luigigimmi/xelatex-docker:latest
```

## How to use it
This docker image contains texlive in order to build your latex files.

You can use it iteratively by executing:
```
docker run -it -v ${PWD}:/usr/src/app -rm ghcr.io/luigigimmi/xelatex-docker xelatex file.tex
```

## Contributing
Contributions are welcome

## License
[MIT License](LICENSE)
