# RubberDucky-Archive

**DO NOT DO ANYTHING HARMFUL OR ILLEGAL WITH THESE PAYLOADS. I WILL NOT BE HELD RESPONSIBLE FOR ANY DAMAGE.**\
You may need to adjust the delay times depending on the target machine.

[PAYLOADS](https://github.com/Eddie-Devine/RubberDucky-Archive/wiki/Payloads)

**What is a Bad USB?**\
A bad USB is not really USB. It's an [Arduino](https://learn.sparkfun.com/tutorials/what-is-an-arduino/all) that emulates keyboard input. Because human input is trusted by computers, and almost all operating systems support keyboard input, bad USBs are the ultimate hacking tool. By sending keystrokes to the system they can deploy all sorts of malicious attacks from something as deadly as a reverse shell, to funny jokes such as changing the desktop background.

**Where To Buy?**\
Arduino: [Buy](https://www.amazon.com/gp/product/B01MTU9GOB/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)\
Malduino: [Buy](https://maltronics.com/collections/malduinos)\
Rubber Ducky: [Buy](https://shop.hak5.org/products/usb-rubber-ducky-deluxe)

**Setting Up:**\
Arduino: [Set Up](https://www.youtube.com/watch?v=_yJWwKO3_Z0)\
Malduino: [Set Up](https://www.youtube.com/watch?v=cI3xlxGRGKU)\
Rubber Ducky: [Set Up](https://blog.hartleybrody.com/rubber-ducky-guide/)

**Notes:**\
If the scripts are not running properly you are either running them on the wrong operating system or the computer is too slow. To find what OS the script is designed for check the comments at the top (REM). If the computer is too slow up the DELAY times.

When downloading an Arduino script make sure you keep it in the folder it came in and make sure you have the [Arduino IDE](https://www.arduino.cc/en/software) installed.

When you upload a script to an Arduino it runs automatically so make sure not to accidentally run a malicious script on your system.

Arduinos are not removable drives. You cannot store files on them. The only exception is the Rubber Ducky. With twin duck mode the ducky activates a small drive stored inside.

If you want to write your own Arduino scripts you can either learn the Arduino scripting language, or you can write in the much easier Ducky Langauge. Before you upload to an Arduino you have to convert your Ducky script to Arduino script. There are many sites to do this but I recommend [Duckuino](https://dukweeno.github.io/Duckuino/).
