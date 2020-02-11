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