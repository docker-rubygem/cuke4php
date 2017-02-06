[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/cuke4php.svg)](https://hub.docker.com/r/rubygem/cuke4php/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/cuke4php.svg)](https://hub.docker.com/r/rubygem/cuke4php/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/cuke4php.svg)](https://hub.docker.com/r/rubygem/cuke4php/)
[![Gem Downloads](https://img.shields.io/gem/dt/cuke4php.svg)](https://rubygems.org/gems/cuke4php/)
# cuke4php

Auto-Generated Docker image for cuke4php to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/cuke4php`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/cuke4php`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/cuke4php`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/cuke4php/)
