# 64 BIT kernel from [CodePulse's Video](https://www.youtube.com/watch?v=FkrpUaGThTQ)

## You can use this with
----
`docker run --rm -it -v $PWD:/root/env myos-buildenv`
----
`sudo docker build buildenv -t myos-buildenv`
----
`qemu-system-x86_64 -cdrom dist/x86_64/kernel.iso`
----