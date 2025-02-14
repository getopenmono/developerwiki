# Mono Developer Documentation

**This is the developer resources for OpenMono SDK. You can find getting started tutorials, downloads, background articles and API references.**

<h4>Quick Links:</h4>
<center>
<a href="getting-started/install.html" class="btn btn-neutral"><span class="fa fa-cloud-download"></span> Install SDK</a>
<a href="getting-started/hello_world.html" class="btn btn-neutral"><span class="fa fa-code"></span> Hello World Tutorial</a>
<a href="getting-started/arduino-hackers.html" class="btn btn-neutral"><span class="fa fa-microchip"></span> Using Arduino IDE</a>
</center>

```eval_rst
.. image:: sdk.png
    :align: center
    :height: 300px
```



## Content

 * [Getting Started](getting-started/getting_started.md)
 * [Tutorials](tutorials/tutorials.md)
 * [In-Depth Articles](articles/articles.md)
 * [Schematics](schematics/index.md)
 * [Integrating with MonoKiosk](kiosk/monokiosk.md)
 * [Datasheets](datasheets/datasheets.md)
 * [API Reference](reference/reference.md)
 * [Release Notes](release-notes/index.md)

<!-- ### What to find here?

Here on our developer site, we collect all learning resources about mono. You will find initial getting started guides, followed by tutorials on specific topics, in-depth articles and last (but not least) the API reference docs.

We prioritize to get as much text published fast, instead of keeping our cards close. We hope you like our deciscion. Anyway - should you encounter anything you would like to correct - see: [Contributing](#contribute)
-->

<!-- ### Direct Download

Go straight to our download page: [Download SDKs](downloads/index.md)
-->

### Implementation status

As with this site, the software is also being finished right now. The *current status* page include a list of all the planned features of the framework - and their implementation status:

 * **[Current Status](current-status.md)**


### Contribute

The source to this documentation is available publicly on our GitHub. Please just fork it, correct all our *bad engrish* - and submit a pull request. We would just loooove that!

You can contribute to this documentation through the
[GitHub repository](https://github.com/getopenmono/monodocs).
Note that everything you contribute will be free for anyone to use because
it falls under the [site license](LICENSE.md).


### What is Mono anyway?

Haven't you heard the word? Mono is an embedded hardware platform that brings all the goods from [Arduino](http://www.arduino.cc) and [mbed](http://developer.mbed.org) to a whole new level! No fiddling with voltage levels, open-drain vs pull-up configurations. We take care of all this low-level stuff for you. You just focus on building your application, taking advantage of all the build-in hardware functionalities - like:

* Arm Cortex-M3 MCU
* Touch display
* Battery
* Wifi
* Bluetooth
* Accelerometer
* Temperature Sensor
* SD Card
* General Purpose 3.5mm jack connector

On this developer documentation site, you learn how to use all these features through our high-level API.