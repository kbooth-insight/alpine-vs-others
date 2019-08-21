# alpine-vs-others

This is meant as a simple demonstrations that alpine runs slower in some circumstances than things that don't use musclec


## To use this

Either run the `test.sh` or run `docker-compose up --build`

At the end, you will get two outputs, one with the load test results of alpine based python, and one with debian based python.

On my Ryzen 1700 workstation, it's nearly 4x the performance.

This is a simple python3 app using http.server (not meant to be production, but illustrates the point)