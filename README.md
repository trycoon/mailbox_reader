# Mailbox reader
Simple Arduino sketch for detecting when the mailman has delivered new mails in your mailbox.
A cheep [433MHz transmitter](https://www.aliexpress.com/item/Hot-Sale-New-White-433-Mhz-Sensors-Alarms-Contact-Wireless-Door-Window-Magnet-Entry-Detector-Sensor/32505569785.html) with a Reed-sensor is placed on the mailbox, when the lid is opened it transmit a signal to this receiver. The receiver emulates a [Maxim DS2423](https://datasheets.maximintegrated.com/en/ds/DS2423.pdf) 1-Wire counter which could be be monitored by most SmartHome softwares supporting 1-Wire.
