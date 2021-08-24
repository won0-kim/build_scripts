# buildscripts

## docker build

### dmake 

dmake is one of the build scripts using docker. dmake is basically using a docker image to build. 
Therefore, there should be the docker image including all dependency. 

examples)
<pre>
dmake debian . make
dmake arm64v8/ubuntu ./src "./cofigure && make"
dmake mybuild/android /path/to/aosp "source build/envsetup.sh; m com.example.test"
</pre>
