# IoT Engineering
## Hands-on of lesson 8
For slides and example code, see [lesson 8](../../../fhnw-iot/blob/master/08/README.md)

> *Note: Do not work on this repository right away.*<br/>
> *[Check existing forks to find the specific repository for your class.](../../network/members)*

### a) Arduino LoRaWAN, 15'
* Get an account at https://thethingsnetwork.org/
* Register an application with two (Arduino) devices.
* Get ABP keys for one device, OTAA keys for another.
* Run the previous Arduino LoRaWAN .ino examples.
* Make sure to set the pin map, keys in the source

### b) TTN integrations, 15'
* Read the TTN [HTTP](https://www.thethingsnetwork.org/docs/applications/http/) and [MQTT](https://www.thethingsnetwork.org/docs/applications/mqtt/api.html) data API docs.
* Use the Raspberry Pi as an application backend.
* Set up an HTTP Service to log TTN Webhook calls.
* Run a MQTT (sub) client to log incoming messages.

### c) LoRaWAN use cases, 15'
* Which applications become possible with LoRaWAN?
* Does free wide area connectivity change anything?
* Sketch the reference model for an application.
* Find a case that clearly beats Wi-Fi, 3/4G.

### Submitting results
* [Commit and push](#git) local changes to your repository.
* Want a review? [Create an issue](../../issues/new), mention me (@tamberg).

## Tools
### Git
On your computer
* In the hands-on repository [fork for your class](../../network/members), in README.md, click the _GitHub Classroom link_.
* Once you accept the assessment, you get a personal, private repository URL for your _USER_NAME_:<pre>
http://github.com/fhnw-iot-CLASS/fhnw-iot-work-08-USER_NAME</pre>

On your computer or Raspberry Pi
* Clone the repository<pre>
    $ cd ~
    $ git clone REPO_URL</pre>
* Add a file<pre>
    $ git add FILE</pre>
* Commit changes<pre>
    $ git commit FILE -m "Fixed all bugs"</pre>
* Push changes<pre>
    $ git push</pre>

## Wiki
- [IoT Engineering Wiki](https://github.com/tamberg/fhnw-iot/wiki)

## Support
- [IoT Engineering Slack](https://fhnw-iot.slack.com/)
