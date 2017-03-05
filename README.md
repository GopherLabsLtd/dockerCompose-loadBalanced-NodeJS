<img src="https://raw.githubusercontent.com/preciousDev/dockerCompose-loadBalanced-NodeJS/master/preview.jpg" alt="Node.js application loadbalanced by NGINX inside Docker Containers" style="max-width: 100%;" width="650">

![nginx 1.11.10](https://img.shields.io/badge/nginx-1.11.10-brightgreen.svg) ![License MIT](https://img.shields.io/badge/license-MIT-blue.svg)

This is a docker-compose setup running an express app, being load-balanced through NGINX.

All NGINX configs has been intensely commented and explained, as well as the DockerFiles.

### Requirements
- [Docker](https://docs.docker.com/compose/install/ "Docker Compose Install")

### Usage
To run it:

    docker-compose up --build
    
To run the alpine version (5MB image):

    docker-compose -f docker-compose-alpine.yml up --build

### Contributing
If you feel that something is missing, make an issue! 🙂
If you want do add something, just make a Pull Request.

# License
MIT License

Copyright (c) 2017 preciousDev

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
