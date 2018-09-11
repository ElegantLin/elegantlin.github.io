---
title: "Open Source Hardware and Programming (55010501)"
collection: teaching
type: "Teaching Assistant"
target: "Freshmen of D&I"
permalink: /teaching/Open-Source-Hardware-and-Programming
venue: "School of Design and Innovation, Tongji University"
date: Sept. 2018 -- Jan. 2019
location: "Shanghai, China"
---

<!-- TOC -->

- [<div id="preface">Preface</div>](#div-idprefaceprefacediv)
- [<div id="device">Device</div>](#div-iddevicedevicediv)
    - [<div id="processor">Processor</div>](#div-idprocessorprocessordiv)
        - [<div id="arduino">[Arduino](https://www.arduino.cc/)</div>](#div-idarduinoarduinohttpswwwarduinoccdiv)
            - [Introduction](#introduction)
            - [Prerequisites](#prerequisites)
            - [Tutorials](#tutorials)
            - [[Arduino Based Projects]()[^2](More are coming...)](#arduino-based-projects^2more-are-coming)
        - [[Raspberry Pi](https://www.raspberrypi.org/)](#raspberry-pihttpswwwraspberrypiorg)
    - [Sensor](#sensor)
        - [[Real Sense](https://www.intel.com/content/www/us/en/architecture-and-technology/realsense-overview.html)](#real-sensehttpswwwintelcomcontentwwwusenarchitecture-and-technologyrealsense-overviewhtml)
        - [[Kinect](https://en.wikipedia.org/wiki/Kinect)](#kinecthttpsenwikipediaorgwikikinect)
    - [Data Visualization](#data-visualization)
        - [[Processing](https://processing.org/)](#processinghttpsprocessingorg)
        - [[D3.js](https://d3js.org/)](#d3jshttpsd3jsorg)
    - [Suggested Reference[^4]](#suggested-reference^4)
    - [Frequently Asked (Coming Soon)](#frequently-asked-coming-soon)
    - [Reference & Points](#reference--points)

<!-- /TOC -->

Hi, visitors. It's my honor to be one of teaching assistants of Open Source Hardware and Programming (55010501) in the Autumn semester of 2018-2019 Academic Year. This page is for the reference in Open Source Hardware and Programming course. You can find the materials in the following links. If you have any questions about this course and the technology you want to know in this course, please be free to contact me. I will be in [D&I](https://www.amap.com/search?query=%E5%90%8C%E6%B5%8E%E5%A4%A7%E5%AD%A6%E8%AE%BE%E8%AE%A1%E5%88%9B%E6%84%8F%E5%AD%A6%E9%99%A2&city=110000&geoobj=116.322888%7C39.835689%7C116.597546%7C39.979481&zoom=12)  every Monday afternoon. 

Although I have used Arduino, Raspberry Pi and so on in several projects. There must be some topics that I have never known about before. In this course, I will learn with you together. I hope you enjoy this journey and get a big A in this course! Now, let's begin!


#<div id="preface">Preface</div>
One suggestion for you before the journey: *More Searching* using **Google** (never use Baidu, please)[^1], *More practice* and *More thinking*.

Several concepts you should know from the name of this course: [Open Source Software](https://opensource.com/resources/what-open-source), [Open Source Hardware](https://en.wikipedia.org/wiki/Open-source_hardware), [LICENSEs of Open Source software](https://opensource.org/licenses) and [Github](https://en.wikipedia.org/wiki/GitHub).

#<div id="device">Device</div>
After keeping the view of course, you have got the strongest weapon to help you overcome the difficulties in this journey. The next you should do is to know about the physical world.

##<div id="processor">Processor</div>
### <div id="arduino">[Arduino](https://www.arduino.cc/)</div>

#### Introduction

>Arduino is an open-source electronics platform based on easy-to-use hardware and software. Arduino boards are able to read inputs - light on a sensor, a finger on a button, or a Twitter message - and turn it into an output - activating a motor, turning on an LED, publishing something online. You can tell your board what to do by sending a set of instructions to the **microcontroller** on the board. To do so you use the Arduino programming language (based on Wiring), and the Arduino Software (IDE), based on Processing[^3].

>Arduino is an open-source platform used for building electronics projects. Arduino consists of both a physical programmable circuit board (often referred to as a microcontroller) and a piece of software, or IDE (Integrated Development Environment) that runs on your computer, used to write and upload computer code to the physical board.The Arduino platform has become quite popular with people just starting out with electronics, and for good reason. Unlike most previous programmable circuit boards, the Arduino does not need a separate piece of hardware (called a programmer) in order to load new code onto the board – you can simply use a USB cable. Additionally, the Arduino IDE uses a simplified version of C++, making it easier to learn to program. Finally, Arduino provides a standard form factor that breaks out the functions of the micro-controller into a more accessible package[^2].



Further reading of this chapter: 
* [Arduino vs Microprocessor vs Mircocontroller](https://electronics.stackexchange.com/questions/99434/arduino-vs-microprocessor-vs-microcontroller)
* [The History of Arduino](https://arduinohistory.github.io/)
#### Prerequisites
Since you are from different backgrounds, it's necessary to provide some information about the basic electronics. If you have learned these before, you can skip this chapter. However, if you have never learned about Electronics, it is of vital importance to scan these topic [^2]:
> * [What is Electricity?](https://learn.sparkfun.com/tutorials/what-is-electricity)
> * [Voltage, Current, Resistance, and Ohm’s Law](https://learn.sparkfun.com/tutorials/voltage-current-resistance-and-ohms-law)
> * [What is a Circuit?](https://learn.sparkfun.com/tutorials/what-is-a-circuit)
> * [Polarity](https://learn.sparkfun.com/tutorials/polarity)
> * [Integrated Circuits (ICs)](https://learn.sparkfun.com/tutorials/integrated-circuits)
> * [Logic Levels](https://learn.sparkfun.com/tutorials/logic-levels)
> * [Digital Logic](https://learn.sparkfun.com/tutorials/digital-logic)
> * [Analog vs. Digital](https://learn.sparkfun.com/tutorials/analog-vs-digital)
> * [How to use Digital Multi-meter (DMM)](https://baijiahao.baidu.com/s?id=1567351373923100&wfr=spider&for=pc)

#### Tutorials
* Figure out your Arduino (Sorry for link directly to a store page..., I am so lazy...)
    * [Arduino Uno](https://www.sparkfun.com/products/11021?_ga=2.42357282.643416203.1536409448-1871409446.1536409448)
    >The Uno is a great choice for your first Arduino. It’s got everything you need to get started, and nothing you don’t. It has 14 digital input/output pins (of which 6 can be used as PWM outputs), 6 analog inputs, a USB connection, a power jack, a reset button and more. It contains everything needed to support the microcontroller; simply connect it to a computer with a USB cable or power it with a AC-to-DC adapter or battery to get started.
    * [LilyPad Arduino](https://www.sparkfun.com/products/13342)
    >This is LilyPad Arduino main board! LilyPad is a wearable e-textile technology developed by Leah Buechley and cooperatively designed by Leah and SparkFun. Each LilyPad was creatively designed with large connecting pads and a flat back to allow them to be sewn into clothing with conductive thread. The LilyPad also has its own family of input, output, power, and sensor boards that are also built specifically for e-textiles. They’re even washable!
    * [RedBoard](https://www.sparkfun.com/products/13975)
    >At SparkFun we use many Arduinos and we’re always looking for the simplest, most stable one. Each board is a bit different and no one board has everything we want – so we decided to make our own version that combines all our favorite features. The RedBoard can be programmed over a USB Mini-B cable using the Arduino IDE. It’ll work on Windows 8 without having to change your security settings (we used signed drivers, unlike the UNO). It’s more stable due to the USB/FTDI chip we used, plus it’s completely flat on the back, making it easier to embed in your projects. Just plug in the board, select “Arduino UNO” from the board menu and you’re ready to upload code. You can power the RedBoard over USB or through the barrel jack. The on-board power regulator can handle anything from 7 to 15VDC.
    * [Arduino Mega](https://www.sparkfun.com/products/11061?_ga=2.151435198.643416203.1536409448-1871409446.1536409448)
    >The Arduino Mega is like the UNO’s big brother. It has lots (54!) of digital input/output pins (14 can be used as PWM outputs), 16 analog inputs, a USB connection, a power jack, and a reset button. It contains everything needed to support the microcontroller; simply connect it to a computer with a USB cable or power it with a AC-to-DC adapter or battery to get started. The large number of pins make this board very handy for projects that require a bunch of digital inputs or outputs (like lots of LEDs or buttons).
    * [Arduino Leonardo](https://www.sparkfun.com/products/11286?_ga=2.87470751.643416203.1536409448-1871409446.1536409448)
    >The Leonardo is Arduino’s first development board to use one microcontroller with built-in USB. This means that it can be cheaper and simpler. Also, because the board is handling USB directly, code libraries are available which allow the board to emulate a computer keyboard, mouse, and more!
    * [Arduino Nano](https://store.arduino.cc/usa/arduino-nano)
    >The Arduino Nano is a small, complete, and breadboard-friendly board based on the ATmega328P (Arduino Nano 3.x). It has more or less the same functionality of the Arduino Duemilanove, but in a different package. It lacks only a DC power jack, and works with a Mini-B USB cable instead of a standard one. 
    
    Hint: If you want to use Arduino Nano, you have to install the driver first. The instruction is [here](https://sparks.gogo.co.nz/ch340.html). I have tried it on Windows and Mac successfully.

* The component of an Arduino: [Board Description](https://www.tutorialspoint.com/arduino/arduino_board_description.htm)
* Set up your IDE: [Download Links](https://www.arduino.cc/en/Main/Software)
* How to check your environment setup (MAC OS X): 
    1. Set up your IDE based on the instruction above
    2. Connect your PC with your Arduino board. (Make sure your Arduino board is Arduino UNO)
    3. Open your Arduino Software
    4. Click *Tools* -> *Board* -> *'Arduino UNO'*
    5. Click *Tools* -> *Port* -> Select Port different from your PC, e.g. "usbmodem1411(Arduino/Geniuno UNO)
    6. If you can find the port, that means you have set up your environment successfully.
* How to check your environment setup (Windows): [links](https://www.arduino.cc/en/Guide/ArduinoUno)

* Further Reading:
    * [The difference between Windows, Mac OS and Linux](https://www.gonet.com.cn/webduirshow-166.html)
    * [The difference between 32-bit and 64-bit System](https://www.geeksforgeeks.org/difference-32-bit-64-bit-operating-systems/)

* Run a project
* **Project I:** Light an LED
    * What is LED?
    * Breadboard
    * Program Structure
    * Working with Wire
    * Complete Files

#### [Arduino Based Projects]()[^2](More are coming...)
* 

### [Raspberry Pi](https://www.raspberrypi.org/)



## Sensor
### [Real Sense](https://www.intel.com/content/www/us/en/architecture-and-technology/realsense-overview.html)


### [Kinect](https://en.wikipedia.org/wiki/Kinect)


## Data Visualization
### [Processing](https://processing.org/)
### [D3.js](https://d3js.org/)

## Suggested Reference[^4]
* *C++ Primer Plus (6th Version)* [CN(Simplified)](https://www.amazon.com/Primer-Plus-%E4%B8%AD%E6%96%87%E7%89%88-%E7%AC%AC6%E7%89%88-%E5%B9%B3%E8%A3%85/dp/B016G3MLWO/ref=sr_1_1?s=books&ie=UTF8&qid=1536418666&sr=1-1&keywords=C%2B%2B+primer+plus%E4%B8%AD%E6%96%87%E7%89%88) & [EN](https://www.amazon.com/Primer-Plus-6th-Developers-Library/dp/0321776402)
* 

## Frequently Asked (Coming Soon)
* How to setup environment?
* What is the meaning of choices for every board or processor in Arduino Software?


## Reference & Points
[^2]: https://www.arduino.cc/en/Guide/Introduction
[^3]: https://learn.sparkfun.com/tutorials/what-is-an-arduino
[^1]: Google is forbidden in Mainland. I can not share how to do this here or I will be put into jail. If you want to learn more, please contact me offline.
[^4]: Due to the copyright, I can only put the Amazon link here. If you want to learn more, please contact me offline.