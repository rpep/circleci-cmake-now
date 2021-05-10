# circleci-cmake-now

## Archived - this no longer works as CircleCI changed the way settings must be configured. Leaving here for reference only.

CircleCI is great for unit testing in languages like Python and Ruby, but it can take a bit more work to set up C/C++ projects, because the build toolchains need to be set up manually. One of the problems I ran into is that the CMake which is installed by default is only v2.8; the most recent stable version is v3.6. With this repository, you can:
  * Have a working version of CMake in seconds on CircleCI simply by forking the repository.
  * Have a pre-set up cache for CMake, so that it is only installed once.
  * Use the lines from the config file in your own project.
