# circleci-modern-cmake

CircleCI is great for unit testing in languages like Python and Ruby, but it can take a bit more work to set up C/C++ projects. One of the problems currently is that many of the build tools are not up to date due to the version of Ubuntu used.
CMake by default is only 2.8.12.2.

Here is given a simple circle.yml file, which fetches the latest stable release of CMake, and caches this, so that it doesn't have to be redownloaded every time. Hopefully this will help someone save some time, as I couldn't find a guide on how to do this. 
