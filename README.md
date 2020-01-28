# docker-pwndbg

To run this:
```

docker build . -t gdb-tools

docker images  #--to locate the image ID

docker run  --cap-add=SYS_PTRACE --security-opt seccomp=unconfined -i -t <IMAGE_ID>

```
Some labs are located under labs directory and the corresponding tutorials are [here](https://tc.gts3.org/cs6265/2019/tut/tut01-warmup1.html)
 
 Try it out!!!
