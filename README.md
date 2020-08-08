# Super Mario 64 Android Port
This is a port of the reconstructed Super Mario 64 source code to Android.
It uses SDL2 with OpenGL ES 2.0
The port is currently not really good as there's no sound, no touch controls, ect. These will be fixed later.

# Build instructions (Linux)
0. Clone the repo with `git clone https://github.com/VDavid003/sm64-port-android-base.git` and init submodules with `git submodule init && git submodule update.
1. Make sure you can compile the non-Android PC port and copy the base ROM to app/jni/src like you'd normally do.
2. Build the PC version inside app/jni/src. To do this just `pushd app/jni/src` and `make`.
3. After going back to the root folder (`popd`), get SDL with `./getSDL.sh`.
4. Build (and install) using gradle (`./gradlew installDebug`)

# Build instructions (Windows)
Coming soon(tm)