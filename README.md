# esp32-starter-board
A basic project for creating a starter board with an esp32 SoC. 
This is a guide based off of [Robert Feranec's tutorial](https://www.youtube.com/watch?v=S_p0YV-JlfU) on making a custom ESP32 board.

### technical good-to-knows
- [TVS/ESD protection diodes](https://toshiba.semicon-storage.com/info/docget.jsp?did=68869)

### sources
- [espressif devkit docs](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/hw-reference/esp32/get-started-devkitc.html)
- [esp32 datasheet](https://www.espressif.com/sites/default/files/documentation/esp32_datasheet_en.pdf)
- [esp32 devkit schematics](https://dl.espressif.com/dl/schematics/esp32_devkitc_v4_sch.pdf)
- Some components do not exist in standard KiCad library. To use parts available in LCSC or EasyEDA, you can use the following [easyeda-to-kicad converter](https://pypi.org/project/easyeda2kicad/) which relies on LCSC part ids'.
