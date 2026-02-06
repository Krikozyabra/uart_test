# This is test the uart in duplex mode

MTUs: stm32f103c8t6 and esp32

IDE: 
1) Keil for stm32
2) VSCode + esp-idf 5.5.2 for esp32

Langs: C99/C++17

Compiler settings for stm32:
-xc -std=c99 --target=arm-arm-none-eabi -mcpu=cortex-m3 -c
-fno-rtti -funsigned-char -fshort-enums -fshort-wchar
-D__EVAL -gdwarf-4 -O3 -ffunction-sections -Wall -Wextra -Wno-packed -Wno-reserved-id-macro -Wno-unused-macros -Wno-documentation-unknown-command -Wno-documentation -Wno-license-management -Wno-parentheses-equality -Wno-reserved-identifier
-ID:/Users/dalboeb/AppData/Local/Arm/Packs/Keil/STM32F1xx_DFP/2.4.1/Device/Include
-D__UVISION_VERSION="543" -DSTM32F10X_MD
-o ./Objects/*.o -MMD
