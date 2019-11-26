# Clear ELK
A docker-compose with clearwater and elk configured

## Why an ELK on Plug'in ? why not just use Logaas

[Here is why](https://plazza.orange.com/thread/274803)

## What's inside

- Docker compose file with a clearwater configured 
- Filebeat with a config file
- The ELK is deployed on one of Plug'in servers (lucy3)

## About the images

All the images are on my github account. Some of them are also on gitlab.

## live-testing

This is an ongoing work. The docker image is on my github account, the build works. Needs to be thoroughly tested first (this is why it's commented by default, uncomment if you want to use).

## The environment

This PoC works on the innovation network. Which is exactly where Logaas does not work for now.
