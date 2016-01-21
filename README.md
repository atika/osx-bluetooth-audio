# Mac OS X Bluetooth Audio
Connect to a Bluetooth Audio Device on Mac OS X from the cli (python script)

```shell

# List paired devices and help
./BluetoothAudio

# Switch to the device
./BluetoothAudio --name "deviceName" --address "deviceAddress"

# Diconnect
./BluetoothAudio --name "deviceName" --address "deviceAddress" --disconnect

```


Script from my LaunchBar action to connect to Bluetooth audio devices:
[https://github.com/atika/launchbar](https://github.com/atika/launchbar#bluetoothaudio)