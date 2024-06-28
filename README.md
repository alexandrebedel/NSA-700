# NSA-700

NSA Project

# Setting up the runner

1. Go to Admin settings -> CI/CD -> Create a new runner
2. Put a tag for the runner: `docker`
3. Select the operating system: `Linux`
4. Go to the runner console and type: `gitlab-runner register`
5. Write as the gitlab url, the docker machine name: `http://localhost`
6. Choose the executor put it as: `docker`
7. Choose the image `alpine:latest` so it can run on a lightweight linux