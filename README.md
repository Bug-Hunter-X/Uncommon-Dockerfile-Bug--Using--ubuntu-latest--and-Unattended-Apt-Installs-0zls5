This repository demonstrates a common, yet subtle, issue in Dockerfiles: using `ubuntu:latest` and not utilizing the `-y` flag with `apt-get`.  This can lead to unpredictable build times and potential failures due to changing package repositories and unexpected user prompts.

The `Dockerfile` showcases the problem; the `Dockerfile-solution` provides a robust alternative.