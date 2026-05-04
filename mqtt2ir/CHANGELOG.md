# Changelog

## 1.0.0-beta.7

- Added input mode `press` for binary sensor buttons
- Improved input state publishing with retained MQTT state topics
- Improved last-button state publishing with retained MQTT state topics

## 1.0.0-beta.6

- Added MQTT IR blaster bridge topic editing (Edit mode in UI)
- Excluded MQTT blaster bridges from IR Database send targets
- Added raw learned-code preview with copy action in Devices panel

## 1.0.0-beta.5

- Added Zigbee2MQTT ZS06 compatibility:
- Send via `.../set` with `ir_code_to_send`
- Learn trigger via `.../set` with `{"learn_ir_code":"ON"}`
- Learn receive from `learned_ir_code` (JSON and plain text payload support)
- Updated Add MQTT IR Blaster modal with Base/Command/Status/Learn topic fields
