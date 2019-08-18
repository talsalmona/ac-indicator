# A/C indicators
Problem statement: The girls forget to run off the A/C in their room when they go downstairs.
The solution: A simple esphome based setup running on an ESP8266 with two leds that indicate if the girls rooms A/C on the first floor are on.

Details:
1. A/C on/off indication is provided by a Xiaomi [door sensor](https://www.aliexpress.com/item/32829391822.html) installed on the A/C flaps
1. LEDs are defined as switches in [Home Assistant](https://www.home-assistant.io/)
1. Home Assistant [automation](https://github.com/talsalmona/hass-config/blob/5a5dcffa59ede84e97ef37ceb1e34732eacc9302/automations.yaml#L118) to turn the LEDs on and off according to A/C state

 