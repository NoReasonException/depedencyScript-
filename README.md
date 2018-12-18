## ./configure.py
This is a nice script to ensure that every module is installed 
just add a .json file file with the format...
```
  {
    "moduleName1":"command to install in case of non exist1",
    "moduleName2":"command to install in case of non exists2",
         ...
         ...
  }
```
Pass the filename as parameter in main function and everything is ready to go ^^
