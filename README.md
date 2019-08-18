# A/C indicators
**Problem statement**: The girls forget to turn off the A/C in their room when they go downstairs.

**The solution**: An [ESPHome](https://esphome.io/) based setup running on ESP8266 with two leds that indicate if the girls rooms A/C on the first floor are on or off.

**Details**:
1. A/C on/off indication is provided by a Xiaomi [door sensor](https://www.aliexpress.com/item/32829391822.html) installed on the A/C flaps
1. LEDs are defined as switches in [Home Assistant](https://www.home-assistant.io/)
1. Home Assistant [automation](https://github.com/talsalmona/hass-config/blob/5a5dcffa59ede84e97ef37ceb1e34732eacc9302/automations.yaml#L118) to turn the LEDs on and off according to A/C state

**Future Ideal Solution** (not implemented):

Have a **reliable** room presence indicator to turn off the A/C when there's no one in the room. No good solution out there AFAIK.
