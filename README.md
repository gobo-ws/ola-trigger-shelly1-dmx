**OLA trigger config to control Shelly 1/1PM/Plus 1 relay with DMX (Art-Net, sACN or via DMX input)**

**Requirements**  

* [OLA](https://www.openlighting.org/ola/)
* [curl](https://curl.haxx.se/)
* [Shelly 1, 1PM or Plus 1](https://shelly.cloud/)

**Installation**
  
* Download the [shelly1.conf](shelly1.conf) file and edit the configuration section  

[OLA trigger documentation](https://www.openlighting.org/ola/advanced-topics/ola-dmx-trigger/)

**Usage**

* Before running ola_trigger, make sure that olad is running and the universe has been configured with a DMX512 source.  
The config file is provided on the command line:

`ola_trigger shelly1.conf`

