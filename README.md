# golang_alpine
Use docker, they said. It will build the same anywhere, they said. It will run the same anywhere, they said.

So this is a workaround in case you:
* run into the problem described at https://wiki.alpinelinux.org/wiki/Release_Notes_for_Alpine_3.14.0#faccessat2
* want to use a modern version of Go
* and cannot apply any of the workarounds/solutions because of... reasons

This is basically a copy of golang_alpine, only keeping alpine 3.13 so the faccessat2 doesn't raise its ugly head.

Originally comes from: https://github.com/docker-library/golang/tree/master
