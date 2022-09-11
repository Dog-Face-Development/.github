# %PROGRAM NAME% Usage

To install %PROGRAM NAME%, you can use an executable package (Windows), run the scripts through Python (Windows, macOS, Linux), install from the [Python Package Index](https://pypi.org/), or run a [Docker](https://www.docker.com/) container from [GitHub Packages](%GITHUB PACKAGES LINK%). To customize the program to your needs, see [`CUSTOMIZATION`](CUSTOMIZATION.md).

## Executable Package

1. To run the executable package, download the latest `.zip` file from [GitHub Releases](%GITHUB RELEASES LINK%) page.
2. Extract the `.zip` file using a program like [7-Zip](https://www.7-zip.org/).
3. _(Optional) Move the files to `C:\Program Files` and create a shortcut._
4. Double click on `send.exe`.
5. Enjoy the program!

## Python Script

1. To run the Python script, download the latest source code release from [GitHub Releases](%GITHUB RELEASES LINK%) page.
2. Download and install [Python](https://www.python.org/downloads/).
3. Extract the source code files using a program like [7-Zip](https://www.7-zip.org/).
4. Double click on `send.py`, or right-click and open with IDLE and press `F5`.
5. Enjoy the program!

## Python Package Index (`pip`)

1. Download and install [Python](https://www.python.org/downloads/).
2. Open a terminal and run the command: `pip install %PIP COMMAND%`.
3. Start the program by running the command: `%PIP COMMAND%`.
4. Enjoy the program!

## Docker Container

1. Download and install [Docker](https://www.docker.com/products/docker-desktop/).
2. Open a terminal and pull the container: `docker pull %DOCKER PACKAGES LINK%:master`.
3. Start the container: `docker run -i -t %DOCKER PACKAGES LINK% python main.py`.
4. Enjoy the program!
