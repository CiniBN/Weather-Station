# Weather-Station
Weather-Staion Modbus communication ESP32 ESPHome Home Assistant

Időjárás állomás ESP32-vel ESPHome-mal programozva.
Funkciók:
  - Páratartalom [%]
  - Hőmérséklet [°C]
  - Műszerszinti légnyomás [hPa]
  - Tengerszintre számolt légnyomás [hPa]
  - Harmatpont [°C]
  - Szélsebesség [m/s és km/h]
  - Széllökés [m/s és km/h]
  - Szélirány (16 iránymutató)
  - Csapdékmérés az elmúlt 1 órában esett eső [mm/h]
  - Csapdékmérés az elmúlt 1 napban esett eső [mm/d]
  - UV intenzitás [mW/cm²]
  - UV intenzitás [W/m²]
  - UV-index
  - PM1 részecske koncentráció [µg/m³]
  - PM2,5 részecske koncentráció [µg/m³]
  - PM10 részecske koncentráció [µg/m³]
  - Állomás újraindítás

Érzékelők:
  - ComWinTop CWT-BY-THAP hőmérséklet, páratartalom, nyomás kombinált érzékelő
  - RD-RG-AW-0.5 esőmérő ABS RS-485 típus
  - RS-FX-N01 szélirány érzékelő RS-485 típus
  - RS-FS-N01 szélsebesség érzékelő RS-485 típus
  - ComWinTop CWT-UR-S UV intenzitás mérő RS-485 típus
  - Plantower PMS7003 részecske koncentáció mérő

ESP:
  - ESP32-WROOM 38pin

Az állomás akkumulátorról üzemel, amelyhez tartozik egy kapocsfeszültség mérő, típusa: N43VD04 feszültség mérő.
