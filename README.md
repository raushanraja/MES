MES
This repository contains thecollection of errors and the solution for errors that I face.


# IOT -
## 0x1526 B-R to R-B Color correction
```cpp
     uint8_t d[6];
      d[0] = 0xC2;
      uint8_t c0[] = { 0x82 };
      tft.pushCommand(0xC0, d, sizeof(c0));
```

## Python PM2 Error
+ pm2 to run python script
+ https://pm2.keymetrics.io/docs/usage/quick-start/
+ https://stackoverflow.com/questions/49109069/running-a-python-script-with-pm2-error


# Archive
+ zip copy dir with exclude dir `zip -r myarchive.zip dir1 -x "dir1/ignoreDir1/*" "dir1/ignoreDir2/*"`


# Python build
+ Download souce, unzip and go to directory
+ ./configure --enable-optimizations --prefix=$HOME/python3.10
+ make
+ make install
