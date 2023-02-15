# Product Design on Sigfox Radio
 Review approach when designing Sigfox product with Sigfox Radio Modules. 

 ## Introduction 

Sigfox is an IoT network also called **0G** which is inexpensive, reliable, low-power solution and was built to connect sensors and devices. It uses radio-based network, layed infrastructure by the network operator enables your sensors and devices to wisper messages and these messages are transmitted to the base station and to the Sigfox Backend, in that manne, we are able to give voice to the physical world, and make the Internet of Things truly happen.

**The Sigfox protocol focuses on:** 

- *Autonomy.* Extremely low energy consumption, allowing years of battery life.
- *Simplicity.* No configuration, connection request or signaling. Your device is up and running within minutes!
- *Cost efficiency.* From the hardware used in the devices to our network, we optimize every step to be as cost-effective as possible.
- *Small messages.* No large assets or media allowed on the network, only small notifications: up to 12 bytes.
- *Complementarity.* Thanks to its low cost and ease of configuration, you can also use Sigfox as a secondary solution to any other type of network, e.g.: Wi-Fi, Bluetooth, GPRS, etc

For the devices and sensors to communicate, Sigfox do not use WiFi, GSM that relies on Sim cards but uses special chipsets called **Sigfox Radio Modules** 

## Radio Configurations 
Sigfox operates in unlicensed bands worldwide. Due to this nature, global coverage operation radio frequency vary. However, the band range is from 862 to 928 MHz. Due to local regulations, laws or other operating constraints, the network configuration can differ from one country to the other, this results to what is called *Geographical Zones*. Global operations are currently split into seven geographical zones: from RC1 to RC7. More can come as the network adds new countries.
See the map below:

- Each zone has a different set of parameters which clearly dimension the device hardware implementation: mainly *frequency range,* *maximum radiated power,* and *radio front end specificities*

For further details: [Sigfox-Official-Documentation](https://build.sigfox.com/sigfox-radio-configurations-rc)

<img width="679" alt="geographical zones" src="https://user-images.githubusercontent.com/55284959/219023358-625a884d-6a31-4aad-bdc3-aecbc9fceef2.png">


