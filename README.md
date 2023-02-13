# ARM-Runner images with compiled Python


ARM-Runner images, from [RaspiOS lite repo](https://downloads.raspberrypi.org/raspios_lite_armhf/images/), rebuilt to contain 
listed Python, built from sourcecode, into `/opt/build_python/installed` folder.

Made to be used with [arm-runner-action](https://github.com/pguyot/arm-runner-action) when building Python C-extension projects, 
to have available Python's headers and libraries, avoiding compile them on each workflow run.


For full combination of ARM architecture and Python versions, please see assets into 
[Release page](https://github.com/gpongelli/arm-runner-python/releases).


* GitHub: <https://github.com/gpongelli/arm-runner-python>
* Free software: MIT

