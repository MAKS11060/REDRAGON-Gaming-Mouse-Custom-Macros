# REDRAGON Gaming Mouse. Use additional function keys (F13-F24)

## How to use

+ Copy folder ***`MacroDB`*** to ***`%USERPROFILE%\AppData\Roaming\REDRAGON Gaming Mouse\`***
+ Open **`%USERPROFILE%\AppData\Roaming\REDRAGON Gaming Mouse\Confin.ini`**
+ Add to the end of the file
  ```
  [MACRO_LIST]
  0=F13
  1=F14
  2=F15
  3=F16
  4=F17
  5=F18
  6=F19
  7=F20
  8=F21
  9=F22
  10=F23
  11=F24

  ```
+ Run REDRAGON software
  + Select **Custimize**, change **Single key** to **Macro manager** and Select the desired macro
  + Apply.

### Notes:
  Macro file structure **NAME.MSMACRO**
  ```
[Setting]
DefaultDelay=10
DelayType=0
LoopType=0
LoopTime=1
Count=2
Map_0=132
DataH_0=0
DataL_0=104 // Keycode from: https://github.com/dokutan/mouse_m908/blob/6f4e9b5c9fdfc43cd241a0a3d8f9e1736a9588bf/include/data.cpp#L225
Map_1=4
DataH_1=0
DataL_1=104 // Convert hex code 0x68 to decimal 104
```
