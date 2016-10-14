# circleci-cmake-now

CircleCI is great for unit testing in languages like Python and Ruby, but it can take a bit more work to set up C/C++ projects, because the build toolchains need to be set up manually. One of the problems I ran into is that the CMake which is installed by default is only v2.8; the most recent stable version is v3.6.

Here is given a simple circle.yml file, which fetches the latest stable release of CMake, and caches this. To use, simply fork the repository and have a project that has a working CMake immediately, or use the the config.yml file however you like.
