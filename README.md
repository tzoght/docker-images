# docker-images



## Python based docker image with jupyter

To build it:

`docker  build . -f Dockerfile-py-conda-jupyter -t tzoght/py-conda-jupyter`

To run it:

`docker run -p 2222:22 -p 8888:8888 -v $(pwd):/app tzoght/py-conda-jupyter`