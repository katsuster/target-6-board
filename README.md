# target-6-board

`target-6` is an opensource steel targets shooting game.

This is CAD data for I/O board to connect the server board with sensors of steel targets.

Please refer these repositories if you have interest in other modules of `target-6`.

* Client: https://github.com/katsuster/target-6-client
* Server: https://github.com/katsuster/target-6-server


## Requires

* Software
  * KiCad 7.0


## How to use


## Source structures

* ctrl/
  * For controller board
  * Begin or cancel the game by the push button
  * Notify start/end of the game by the beep buzzer
* io/
  * For main board
  * Connect server boards (ex. M5Stamp C3), controller and sensor boards
* sensor/
  * For sensor board
  * Detect the hit of BB bullet on steel plate


## Other documents

* [Parts list](doc/parts_jlcpcb.md)
