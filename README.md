# neonious one table radar

This is the table radar, an example project for the neonious one Technology Preview microcontroller board.

It implements an radar for your table, which detects items in short range. You can view the radar through your web browser.

A video of the table radar in action: https://drive.google.com/file/d/1G6cykg5DXdzrsAG8MDHQRWeSNzXArNSn/view


## Why did I create this project?

LED strips, home automation, R/C cars, robotics... We are JavaScript fans and believe its asyncronous nature makes it a great language not only for web sites and servers, but also for IoT. Traditional microcontroller programming just gets difficult when Internet comes into play, or when multiple things are done in parallel (FreeRTOS multithreading: love it or hate it...).

Because of this we designed neonious one: A microcontroller board, programmable and debuggable with a full debugging interface out of box in an on-board web-based IDE, combining JavaScript ES 6, TypeScript, Node.JS API and modules with Internet (Ethernet + Wifi) directly on the board.

This project is a show case to highlight how development with neonious one can be fun and produce unique results :-)

More information about the neonious one board: http://www.neonious.com/


## Hardware setup

The hardware consists of

- a neonious one Technology Preview board
- a servo motor (a motor which you can position at any angle)
- a distance sensor mounted onto the servo motor with glue
- a 5 V power supply

The servo motor is just one I picked of the shelf. You can take any one, as the protocol is standarized (one pulse of about 1 ms to position the servo).

The distance sensor is the Pololu Carrier with Sharp GP2Y0A60SZLF Analog Distance Sensor 10-150cm, 3V. It gives out an analog signal which we can read out easily with the ADC (analog to digital converter) of the board. There are cheaper options, but I had one left from an older project.

The servo motor is connected to the board via pin 6. The distance sensor is connected via pin 8 (which supports ADC).


## Authors

* **Thomas Rogg** - *Initial work*


## License

This project is public domain. Do whatever you like with it.


## Support our Kickstarter!

Really, if you like the project, support us! Post about us on social media, spread the word or just take part in the Kickstarter
yourself.

