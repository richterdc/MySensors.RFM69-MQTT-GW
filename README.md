# MySensors.RFM69-MQTT-GW
MySensors Based RFM69HW and W5100 Based Ethernet MQTT Gateway

Needs a bit of cleanup and formatting changes, i pulled this all together from various resources on the mysensors forum, homeassistant forums and other blogs and forums aroudn the internet. I dont have all references account for so if you see some of your work please let me know and i will add your tag in.

Future Updates will include Eagle Board design and updates logic level converter and stl files for a case.

For antenna i used a simple straight wire as noted on Mysensors site, this seems to cover my house incredibly well from the basement. So should be adequate for most anyone.

For power I am using the onboard regulator of an Arduin Nano clone this appears to be able to power both the W5100 and the RFM69 via USB input. Make sure to use a good usb power source.
