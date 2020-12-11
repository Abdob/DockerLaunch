Build the base container

cd cpp-build-base

docker build . -t cpp-build-base:0.1.0

Build the app container using the base container

cd hello-world

docker build . -t hello-world:1.0.0


