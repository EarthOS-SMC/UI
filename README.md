# EarthOS user interface (login screen)
This is a part of EarthOS; the build system uses this repository for the `/lib/system/ui` file.

## Building from source

Clone this repository using this command:

`git clone https://github.com/EarthOS-SMC/UI`

Then, go to the source code directory:

`cd UI`

Before the build process, you need to clone the PowerSlash compiler too:

`chmod +x sync.sh && ./sync.sh`

To build,

`./build.sh`


The binary will be saved in the `image` file.

## Reduce output

You can reduce the output by putting `1` in the `reduce` file:
`echo 1 > reduce`
