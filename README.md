# RemoteSwitch
12v accessory switch controller with remote interface for automotive application

# Goals
* RS485 connection to switch panel
* RS485 connection to auxiliary remoteswitch boards
* Scalable design, 4, 8, 16 IO lines
* Optoisolated input ports, example ignition (run) and key on (acc) triggers
* Integerated eFuse with external fuse for safety
* Configure each output for continious, accessory or engine running outputs
* Basic logic to link inputs / outputs (AND, OR, NOT)
* Control panel using touch-screen ESP32 or Raspberry Pi type device

# Electronic Fuse
* Programmable current limit
* Analog current sensor (ACS712 or similar)
* N-Channel MOSFET switch
* Boost converter to drive mosfet at 24v
* AVR supervisor circut