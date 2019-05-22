Pulse Secure Services Director
===

Pulse Secure Services Director is the management tool for Pulse Secure Virtual Traffic Manager (vTM), an advanced Application Delivery Controller.

See the [Pulse Secure vADC landing page](https://www.pulsesecure.net/vadc) for more details on the products and their capabilities.

About this Repository
===
One of the features of Services Director allows you to simplify and automate the configuration of vTMs by applying Application Templates. This repository contains Application Templates that can be used by Services Director to automatically configure your vTMs.

About Application Templates
===
An Application Template represents a typical configuration for a specific application, such as a web server. Each application template is supplied as a ".zip" file, which can be installed on Services Director.

Certain fields within a template, such as the IP addresses of backend nodes or certificates used, can be customised before the template is applied to any vTMs. An Application Template, coupled with values for such fields and a vTM cluster it should be applied to, is represented by a Template Instance. After installing the template, creating a Template Instance from it will result in it being applied to the chosen vTM cluster.

Questions
===
If you have a Pulse Secure Services Director license with support entitlement, please contact the Pulse Secure support team with any questions.

Further Information
===
Please see the documentation for the relevant version of Services Director for detailed instructions on how to install and use these templates.

License
===
The files in this repository are licensed under the terms of [Apache License 2.0](./LICENSE). See the LICENSE file for details.
