# STM32F411 Discovery USB HID Mouse

![STM32F411](https://img.shields.io/badge/STM32F411-Discovery-03234B?logo=stmicroelectronics&logoColor=white)
![USB](https://img.shields.io/badge/USB-HID_Device-2496ED?logo=usb&logoColor=white)
![HAL](https://img.shields.io/badge/STM32-HAL_Library-03234B?logo=stmicroelectronics)

<img src="https://github.com/user-attachments/assets/c8a63e13-402d-4585-8295-395baf2fe55c" width="650" alt="BFEE5AF6-5B92-4060-BFC3-6C82D1C010E6">



## Key Features
- ✅ **Plug-and-play** USB HID mouse compliance  
- 🔵 Onboard **blue USER button** (PA0) trigger  
- ⚡ **96MHz** clock via 8MHz HSE + PLL  
- 🖱️ Standard **4-byte HID report** (buttons/X/Y/wheel)  

## Hardware Setup
| Function       | Pin  | Board Location | Badge |
|----------------|------|----------------|-------|
| USER Button    | PA0  | Blue button    | ![GPIO](https://img.shields.io/badge/GPIO-PA0-yellow) |
| USB FS         | PA11/PA12 | CN5 connector | ![USB](https://img.shields.io/badge/USB-Full_Speed-blue) |

## Default Behavior
1. Plug in USB to CN5 (marked "USB USER")
2. Board enumerates as HID mouse
3. Press blue USER button to:
   - Move mouse right by 100 units
   - 200ms debounce delay between events
