Access to Paperspace machine
ssh paperspace@209.51.170.244

Running DIGITS
Running DIGITS: docker run --gpus all -it --rm -v ~/Desktop/docker_share:/data/mnist nvcr.io/nvidia/digits:19.09-tensorflow

Docker commands
Show all containers: docker ps -a
Remove container: docker container rm eed908866b00
Stop container: docker stop c1ac1842a3ec

Resource
https://docs.nvidia.com/deeplearning/digits/digits-container-getting-started/index.html
