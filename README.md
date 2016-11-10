# mailbox_reader
Simple Arduino sketch for detecting when the mailman has delivered new mails in your mailbox.
A cheep [433MHz transmitter](https://www.aliexpress.com/item/Hot-Sale-New-White-433-Mhz-Sensors-Alarms-Contact-Wireless-Doo) with a Reed-sensor is placed on the mailbox, when the lid is opened it transmit a signal to this receiver. The receiver emulates a Maxim DS2423 1-Wire counter which could be be monitored by most SmartHome software supporting 1-Wire.
