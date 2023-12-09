# Geek-Aire-Fan-BF1S
Geek Aire BF1S Tasmotized and enabled with MQTT to allow completely local control

Tasmotized fan can be used with MQTT completely locally in systems such as homeassistant and openHAB.

Internal TuyaMCU controls and stats are mapped to MQTT with the provided config.
(Some values such as UUID are dynamic/specific to my device/system as dumped from my openHAB instance and can be ignored.)


NOTE: The generic Tasmota binary by default only exposes the top level ON/OFF ontrol to tasmota integration in homeassistant.
