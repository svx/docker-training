[![CircleCI](https://circleci.com/gh/wundertax/docker-training.svg?style=svg)](https://circleci.com/gh/wundertax/docker-training)

# Docker Training

## About

Basic training exercises for [Docker](https://docker.com).

## Dependencies

- [Docker](https://docker.com)
- [Docker Compose](https://docs.docker.com/compose/)
- [GitHub](https://github.com) account
- Git installed
- A [Docker Hub](https://hub.docker.com) account

## Building

Change into the various directories and ``build`` the image.

We will use *static-site* for example.

First we ``clone`` the repository.

To do so, please open a terminal or use [GitHub Desktop](https://desktop.github.com/).

If you use the terminal do

``` console
git clone https://github.com/wundertax/docker-training
```

If you use GitHub Desktop, please read the [user guide](https://help.github.com/desktop/guides/).

Change into the directory *static-site*

``` console
cd static-site
```

Build the image and tag it with a name

``` console
docker build -t my-static-webiste .
```

Or with a name of your choice.

## Running The Image

```console
docker run -p 2015:2015 my-static-webiste
```

Now open your browser and browse to: http://0.0.0.0:2015/

## Exercises

- static-site
- share-data
- compose-wordpress

## Contributing

Pull requests are welcome.

For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
