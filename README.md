# ESP32-S3 + 4" Kijelző (ST7701 + GT911) Tasmota Projekt

## Leírás
Ez a projekt egy ESP32-S3-4848S040 kijelzőpanelt használ Tasmota firmware-rel, teljes LVGL felülettel, érintéssel és MQTT integrációval.

## Használt hardver

**ESP32S3-4848S040C-I**  
- 4.0" 480x480 IPS kijelző (ST7701 driver)  
- GT911 kapacitív érintőpanel  
- ESP32-S3 (WROOM) chip  
- 16MB flash / 8MB PSRAM

A kijelző tökéletesen működik a Tasmota 14.5.0.3 lvgl-haspmota firmware-rel és az ESP32S3-4848S040.autoconf fájllal.

## Firmware
- Verzió: 14.5.0.3 (lvgl-haspmota)
- Letöltés: https://github.com/Jason2866/Tasmota-specials/blob/firmware/firmware/tasmota32/other/tasmota32s3-qio_opi.bin

## Autoconf fájl
- Letöltés: https://github.com/arendst/Tasmota/files/14019279/ESP32S3-4848S040.autoconf.zip
- FONTOS: ne csomagold ki! Nevezd át `ESP32S3-4848S040.autoconf` névre feltöltés előtt.

## Home Assistant integráció (következő lépés)
- MQTT konfigurálása
- Állapot megjelenítés
- Entitásvezérlés a kijelzőről
