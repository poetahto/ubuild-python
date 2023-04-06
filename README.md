# ubuild-python
A python API for building Unity projects.

## How to use
- The file [ubuild.py](https://github.com/poetahto/ubuild-python/blob/main/ubuild.py) contains the main API for creating builds of Unity projects. Other python scripts should reference it and call into its helper functions. It also has no external dependencies, so you should be able to use it anywhere.

- The file [unity_build.py](https://github.com/poetahto/ubuild-python/blob/main/unity_build.py) is a quick demonstration of a python script consuming the API. It can be run and prints basic debugging information to the console as it generates a build. It is intended to be placed in the root of any Unity project, and is still a work in progress as it has some information hard-coded for now. Ideally, you would make your own version, or change it to suit your needs.

## TODO Stuff
1) Test ubuild on windows 32, OSX, and linux.
2) Improve the demo script, so that it can become a more reusable quickstart for dropping into projects.
3) Create and serialize some per-project build information, noted in the code for unity_build.py.
4) Maybe come up with a better name for files in this repo, so its more clear what each module does.
