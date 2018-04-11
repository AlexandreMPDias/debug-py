[![N|Solid](https://i.imgur.com/rUMbDaZ.png)](https://cyberlabs.com.br)
# Debug-py
Debug-py is a package created by Cyberlabs to help in debugging and logging.


Used for code debugging.
Contains the following classes:

    Log:
        error(String)           : returns self
        sucess(String)          : returns self
        warn(String)            : returns self
        info(String)            : returns self
        color(Color, String)    : returns self
        split(Color)            : returns self
        **critical(String)      : returns self
  and    

    IntegrityTest:
        isValidProcess(Process, String)      : returns True/False
        isCameraConnected(Boolean)           : returns True/False
        canLocateFile(String, String)        : returns True/False
        canLocateDir(String, String)         : returns True/False
        **isNone(Object, String)             : returns self
        **performInitialChecks()             : returns self
        hasInternetConnection() [not tested] : returns self

[** = not yet implemented]

# Requirements
Requires installation of colorama: 
| Package | Site |
| ------ | ------ |
| Colorama | [https://pypi.python.org/pypi/colorama][PlDb] |

or you can simples run:
```sh
pip install colorama
```


# Notes: 
    -- Not designed to be Thread safe.
    -- Debug-level doesnt work yet
