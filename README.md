# buildscripts

## build on docker

### maked 

maked is one of the build scripts using docker. maked is basically using a docker image to build. 
Therefore, there should be the docker image including all dependency. 

examples)
<pre>
maked debian . make
maked arm64v8/ubuntu ./src "./cofigure && make"
maked mybuild/android /path/to/aosp "source build/envsetup.sh; m com.example.test"
</pre>

by won0
