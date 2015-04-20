# docker-scripts-tester

This image is designed for running the unit test of the scripts repo at switchconcepts.

## Usage

Checkout the scripts repo and run

```bash
docker run -v $PWD/..:/scripts --rm -it swco/scripts-tester go test ./tests -v
```

to run the tests
