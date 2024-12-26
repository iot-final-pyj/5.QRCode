### platformio.ini
```
lib_deps = 
	bodmer/TFT_eSPI@^2.5.43
```
### customize User_Setup.h
find the User_Setup.h
```
find . -name User_Setup_Select.h
```

and modify User_Setup_Select.h
1. comment out the following line
```
//#include <User_Setup.h>           // Default setup is root library folder
```
2. uncomment the following line
```
#include <User_Setups/Setup206_LilyGo_T_Display_S3.h>
```
<img width="475" alt="Screenshot 2024-10-01 at 6 24 39 PM" src="https://github.com/user-attachments/assets/6db0a2fe-6da8-43a7-87c9-924d9c320e30">
