# docker-lastools
lastools for docker 

## Example command to run.

docker run \\ \
-v /host/path/input:/input \\ \
tleisara/lastools \\ \
lasinfo \\ \
-i /input/filename.las \\ \
-repair
