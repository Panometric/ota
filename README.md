# OTA Secure update of firmware over HTTPS

Place the binary with the:

1. Version prefix = project name + "_"
1. Version suffix = version to load + ".bin"
1. Send via MQTT the RPC call "setFirmwareVersion" with the bare parameter of the version to install, such as "0.1.34"

* Example : HVACGateway_0.1.34.bin , send "0.1.43"
