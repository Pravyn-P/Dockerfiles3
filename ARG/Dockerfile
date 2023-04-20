ARG VERSION
#FROM almalinux:${VERSION}
# docker build -t arg:v1 --build-arg VERSION=8 .    --> To create the image by providing version at runtime.
FROM almalinux:${VERSION:-8}   
# The above syntax is to set the default version if any version is not provided at runtime.