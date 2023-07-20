# Apine Docker

## Pull Docker
```bash
docker pull x3platform/openjdk
```

## Build Docker
```bash
# login
docker login -u [USERNAME] -p [PASSWORD]

# build
docker buildx build --push --tag x3platform/openjdk:11-jdk --platform linux/amd64,linux/arm64 --file ./build/Dockerfile ./build/
```
