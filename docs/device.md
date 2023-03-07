# Device

All the bits and pieces that make up the BBC micro:bit

![micro:bit board layout](/static/mb/device-v2.jpg)

### ~ hint


## LED Screen and Status LED

The red lights are [LEDs](/device/screen) (light emitting diodes) and form a 5 x 5 LED Screen. 
They can be set to on/off and the brightness can be controlled.

The yellow light on the back of the micro:bit is the status LED.
It flashes yellow when the system wants to tell the user that something has happened.

See how the @boardname@ shows numbers, text, and displays images by watching this video about LEDs:

https://www.youtube.com/watch?v=qqBmvHD5bCw


## Buttons

Buttons **A** and **B** are a form of input.  When you press a button, it completes an electrical circuit. 
The micro:bit can detect either of its two buttons being pressed/released and be programmed 
to act on these events.

Button **R** on the back of the micro:bit is a system button. It has different uses. 
When you have downloaded and run your code onto your micro:bit, press Button **R** to restart and run your program from the beginning.

Find out how buttons provide input to the @boardname@ in this video:

https://www.youtube.com/watch?v=t_Qujjd_38o

## Touch

Pins **0**, **1**, **2**, and the board **logo** can work as touch buttons when they are programmed for input.

### ~ hint

#### Open the version file

### ~

## Accelerometer

There is an accelerometer on your micro:bit which detects changes in the micro:bit’s speed. 
It converts analogue information into digital form that can be used in micro:bit programs. 
Output is in milli-g. The device will also detect a small number of standard actions e.g. shake, tilt and free-fall.

Watch this video to learn how the accelerometer works:

https://www.youtube.com/watch?v=byngcwjO51U


## Light level

The screen can also be used a light level sensor (it's a really cool trick).

Learn more about how light level is detected in this light sensor video:

https://www.youtube.com/watch?v=TKhCr-dQMBY

## Compass

The compass can detect magnetic fields such as the Earth’s magnetic field. 
As the micro:bit has this compass, it is possible to detect the direction it is moving in. 
The micro:bit can detect where it is facing and movement in degrees. 
This data can be used by the micro:bit in a program or be sent to another device.


## Pins

The [pins](/device/pins) can be a form of electrical input or output. 
There are labels for the input/output pins **0**, **1**, **2**, which you can attach external sensors to such as thermometers or moisture detectors.

## Microphone

Using the microphone, your programs can detect sounds that are present. You can check for loud or quiet sounds and find out what their sound level is.


## Temperature

Temperature is measured on the @boardname@ by detecting how hot its physical CPU material is. Since it operates nearly as cool as the air around it, the temperature it measures for itself is a good approximation for the ambient temperature (the temperature near and around it).

See how the @boardname@ can detect hot or cold in this temperature sensing video:

https://www.youtube.com/watch?v=_T4N8O9xsMA


## How do I connect the micro:bit to my computer?

Your micro:bit can be connected to your computer via a micro USB cable. 
Data can be sent and received between the micro:bit and the computer so programs 
can be downloaded from Windows, Macs and Chromebooks onto the micro:bit via this USB data connection. 
[Click here to read more information on how to run scripts on your micro:bit](/device/usb), 
and [click here to read more about the error messages you might get](/device/error-codes).

## Powering your micro:bit

When your micro:bit is connected to your computer with the micro USB, it doesn’t need another power source.  
When your micro:bit isn’t connected to your computer, tablet or mobile, you will need 2 x AAA 1.5 V batteries to power it.

The pins labelled **3V** and **GND** are the power supply pins. 
You can attach an external device such as a motor to these and power it using the battery or USB.


## Bluetooth Low Energy (BLE) Antenna

You will see the label BLE ANTENNA on the back of your micro:bit. It is for a messaging service, 
so that devices can talk to each other. The micro:bit is a peripheral 
device which can talk to a central device like a smart phone or tablet that has Bluetooth Low Energy (BLE). 
The micro:bit can send signals and receive signals from a central device so another BLE device can 
control the micro:bit or the micro:bit can control another BLE device.

