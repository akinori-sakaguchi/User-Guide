# ESC設定

ESC（Electric Speed Controller）はブラシレスモータの回転数を制御する電子デバイスである．ESCには[Racerstar RS30A V2](https://m.racerstar.com/racerstar-rs30a-v2-30a-blheli_s-esc-opto-2-4s-support-oneshot42-multishot-16_5-dshot600-p-9.html)を使用する．

設定ソフト：[BLHeliSuite](https://www.dropbox.com/sh/gf9d1r52t4v7ol4/AADr8AnqXNqYemk4Or9OGfOWa?dl=0)

Make Interfaces
* Arduino Board: Nano w/ ATmega328(UNOを使用)
* Baud: 115200
* Arduino BLHeli Bootloader

Pinouts
Arduino UNO    ESC
   　GND-------GND   
     D3--------Signal


Select ATMEL/ SILABS Interface
-> C SILABS Bootloader(USB/Com)

Select Port -> Connect -> Read Setup