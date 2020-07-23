 
<!-- Write your comments here -->
<!-- Edited by Chris Grant 2020-07-23 -->
<!-- TODO: Need to update this file to convey relevant information on rhadoop containers -->

# `rhadoop`:  An `rcompute` Module for Distributed Data

### Build the Containers
To build `rhadoop` using `docker-compose`, run the following in the base build directory:
```console
r-user@computer:~$ bash ./start.sh build 
```
```shell script
bash ./start.sh build
```
[rconnect](http://localhost:8787)

Note, if there are already Docker containers for other `rcompute` modules, all additional modules, 
including `rhadoop` will share a common network in Docker called `rconnect`.  If this network does 
not already exist, the `docker-compose up` will create it.


<!-- Write your comments here 

## This repo is now read-only for the source code part. 

The issues will be progressively closed and transitioned to one of the specific repos. The wiki will remain here.


This repo is no longer used to develop the RHadoop packages, which have moved into separate repos: 
+ [rhdfs](https://github.com/RevolutionAnalytics/rhdfs), 
+ [rhbase](https://github.com/RevolutionAnalytics/rhbase), 
+ [rmr2](https://github.com/RevolutionAnalytics/rmr2), 
+ [plyrmr](https://github.com/RevolutionAnalytics/plyrmr),
+ [ravro](https://github.com/RevolutionAnalytics/RHadoop/wiki/user%3Eravro%3EHome)

## Refer to the [wiki](https://github.com/RevolutionAnalytics/RHadoop/wiki) for more information.

-->