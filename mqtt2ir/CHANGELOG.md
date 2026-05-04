# Changelog

## 1.0.0-beta.5

- Added Zigbee2MQTT ZS06 compatibility:
- Send via `.../set` with `ir_code_to_send`
- Learn trigger via `.../set` with `{"learn_ir_code":"ON"}`
- Learn receive from `learned_ir_code` (JSON and plain text payload support)
- Updated Add MQTT IR Blaster modal with Base/Command/Status/Learn topic fields
