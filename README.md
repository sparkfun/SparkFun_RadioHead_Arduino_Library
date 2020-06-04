SparkFun RadioHead Arduino Library
========================================

This is the SparkFun fork of the RadioHead library by Mike McCauley. The original library can be found here: http://www.airspayce.com/mikem/arduino/RadioHead/

Description from the original documentation: 
-------------------------------------------
_This is the RadioHead Packet Radio library for embedded microprocessors. It provides a complete object-oriented library for sending and receiving packetized messages via a variety of common data radios and other transports on a range of embedded microprocessors._

_The version of the package that this documentation refers to can be downloaded from http://www.airspayce.com/mikem/arduino/RadioHead/RadioHead-1.41.zip You can find the latest version at http://www.airspayce.com/mikem/arduino/RadioHead_
_You can also find online help and discussion at http://groups.google.com/group/radiohead-arduino Please use that group for all questions and discussions on this topic. Do not contact the author directly, unless it is to discuss commercial licensing. Before asking a question or reporting a bug, please read:_
_http://en.wikipedia.org/wiki/Wikipedia:Reference_desk/How_to_ask_a_software_question_
_http://www.catb.org/esr/faqs/smart-questions.html_
_http://www.chiark.greenend.org.uk/~shgtatham/bugs.html_

_**Overview**_

_RadioHead consists of 2 main sets of classes: Drivers and Managers._

_Drivers provide low level access to a range of different packet radios and other packetized message transports. Managers provide high level message sending and receiving facilities for a range of different requirements.
Every RadioHead program will have an instance of a Driver to provide access to the data radio or transport, and a Manager that uses that driver to send and receive messages for the application. The programmer is required to instantiate a Driver and a Manager, and to initialise the Manager. Thereafter the facilities of the Manager can be used to send and receive messages._

_It is also possible to use a Driver on its own, without a Manager, although this only allows unaddressed, unreliable transport via the Driver's facilities.
In some specialised use cases, it is possible to instantiate more than one Driver and more than one Manager.
A range of different common embedded microprocessor platforms are supported, allowing your project to run on your choice of processor.
Example programs are included to show the main modes of use._

Repository Contents
-------------------

* **/examples** - Example sketches for the library (.ino). Run these from the Arduino IDE. 
* **/extras** - Additional documentation for the user. These files are ignored by the IDE. 
* **/src** - Source files for the library (.cpp, .h).
* **library.properties** - General library properties for the Arduino package manager. 

Documentation
--------------

* **[Installing an Arduino Library Guide](https://learn.sparkfun.com/tutorials/installing-an-arduino-library)** - Basic information on how to install an Arduino library.
* **[Product Repository](https://github.com/sparkfun/RFM22_Shield-434MHz)** - Main repository (including hardware files) for the RFM22 Arduino Shield.

License Information
-------------------

This product is _**open source**_! 

Please see the LICENSE.md file for more information. 

Distributed as-is; no warranty is given.

- Your friends at SparkFun.

_Based off of the original RadioHead library by Mike McCauley_
