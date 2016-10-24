# Arduino_Cores
Arduino cores (sources) for integrate the "HAL" Arduino functionality in others IDEs

---

**Core extraction process:**

1 - Make a folder named Arduino_Core

2 - Copy inside that folder the sources of the next paths:

  * Arduino:
    * C:/.../Arduino/hardware/arduino/avr/cores/arduino
    * C:/.../Arduino/hardware/arduino/avr/variants/VARIANT
    * C:/.../Arduino/hardware/arduino/avr/libraries/LIBRARY/src
    
  * Other device:
    * C:/Users/PCUSER/AppData/Local/Arduino15/packages/DEVICE/hardware/VERSION/cores/arduino
    * C:/Users/PCUSER/AppData/Local/Arduino15/packages/DEVICE/hardware/VERSION/variants/VARIANT
    * C:/Users/PCUSER/AppData/Local/Arduino15/packages/DEVICE/hardware/VERSION/libraries/LIBRARY/src
