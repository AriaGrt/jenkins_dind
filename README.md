# Jenkins:dind

Jenkins docker installation enabling docker agent creations withint the container for deployment testing

## Installation

```
docker build -t jenkins:dind .
```

## Running
```
docker run --privileged -it -p 8080:8080 jenkins:dind 
```

## Project Status
Working on a complete Docker Hub ready image where no dockerd-entrypoint.sh is needed

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
