Requirement : vs2019 with UWP toolchain

Create custom install.tar.gz from a docker container via "docker export --output=install.tar CONTAINER"

Gzip install.tar into install.tar.gz

Copy install.tar.gz in x64\install.tar.gz

Open developer command prompt and run "build x64 release.bat"

Ignore the compiling error about cmd exiting with -1, if the .appx file is created into "x64\Release\DistroLauncher-Appx\Upload\" it's fine.
