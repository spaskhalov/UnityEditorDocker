# UnityEditorDocker
Docker editor image with some extensions. This repository based on [UNITY CI Images](https://github.com/game-ci/docker). 
## Changes
- Added link form python3 to python, to build firebase correctly.

## How to use
1. Build docker image with a corresponding base image: `docker build --build-arg base_image=unityci/editor:2020.2.3f1-android-0 .`
2. Commit & push to docker hub.
3. Pass image to unity-builder image with `customImage` argument.
