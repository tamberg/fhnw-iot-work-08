# IoT Engineering
## Hands-on of lesson 8
For slides and example code, see [lesson 8](../../../fhnw-iot/blob/master/08/README.md)

> *Note: Do not work on this repository right away.*<br/>
> *[Check existing forks to find the specific repository for your class.](../../network/members)*

### a) Arduino LoRaWAN, 15'
* Get an account at https://thethingsnetwork.org/
* Register a TTN application, and register two devices.
* Get ABP keys for one device, OTAA keys for another.
* Set these keys in the LoRaWAN .ino code examples.
* Make sure to use the right code for your hardware.</br>
  (The pin mapping varies for ESP8266, nRF52840.)

### b) TTN integrations, 15'
* Read the TTN [MQTT](https://www.thethingsindustries.com/docs/integrations/mqtt/) and [Webhooks](https://www.thethingsindustries.com/docs/integrations/webhooks/) API docs.
* Use the Raspberry Pi as your application backend.
* Use a [MQTT SUB client](https://github.com/tamberg/fhnw-iot/blob/master/07/Nodejs/MqttSubClient.js) to log incoming messages.
* Set up an [HTTP Logger](https://github.com/tamberg/fhnw-iot/blob/master/08/Nodejs/HttpLogger.js) to see TTN Webhook calls.

### c) LoRaWAN use cases, 15'
* Which applications become possible with LoRaWAN?
* Does free wide area connectivity change anything?
* Sketch the reference model for an application.
* Find a case that clearly beats Wi-Fi, 3/4G.
