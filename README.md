# pi-food-computer
This project provides foundations for building a food computer using a Raspberry Pi.

## Hardware requirements
### Monitoring
- [Raspberry Pi](https://www.raspberrypi.com/products/) (3B+ or better)
- [Whitebox labs tentacle T3](https://www.whiteboxes.ch/shop/whitebox-t3-for-raspberry-pi/) or [Atlas Scientific i3 Interlink](https://atlas-scientific.com/electrical-isolation/i3-interlink/)
- [pH circuit](https://atlas-scientific.com/embedded-solutions/ezo-ph-circuit/)
- [pH probe](https://atlas-scientific.com/probes/consumer-grade-ph-probe/) (consumer grade or better)
- [Conductivity circuit](https://atlas-scientific.com/embedded-solutions/ezo-conductivity-circuit/)
- [Conductivity probe](https://atlas-scientific.com/probes/mini-e-c-probe-k-1-0/)
- [Temperature circuit](https://atlas-scientific.com/embedded-solutions/ezo-rtd-temperature-circuit/)
- [Temperature probe](https://atlas-scientific.com/probes/standard-temp-probe/)

## Supplies
- pH calibration solutions [Atlas Scientific](https://atlas-scientific.com/ph)
- EC calibration solutions [Atlas Scientific](https://atlas-scientific.com/conductivity)

## Setup
Prerequisite: Follow manufacturer guides to setup raspberry pi and each sensor

- Install [Atlas IOT monitoring software](https://atlas-scientific.com/downloadable/atlas-iot-software/)
- TODO Follow Atlas guide to [setup MQTT](https://files.atlas-scientific.com/Atlas-iot-settings-guide.pdf)
- Follow guides to setup prometheus and grafana monitoring
- TODO Publish [MQTT to Prometheus](https://github.com/hikhvar/mqtt2prometheus)

## Notes:
- TODO Solution Control [Dosing pumps](https://atlas-scientific.com/kits/ezo-pmp-kit/)
- TODO 115v lighting or appliance control [TPLink outlets](https://github.com/jonbenfri/smart-plug-control)
- TODO Raspberry pi camera with ndvi... ndvi requires opencv which isn't buidling on my raspberry pi
