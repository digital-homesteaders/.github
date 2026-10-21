<p align="center">
  <img src="https://avatars.githubusercontent.com/u/345983678?s=160" width="96" alt="Digital Homesteaders icon">
</p>

<h1 align="center">Digital Homesteaders</h1>

<p align="center"><em>Your devices, your hub, your code.</em></p>

Homesteaders grow their own food and live off their own land. We do the same with our smart homes:
open-source drivers and apps that bring devices into the hub *you* run, instead of waiting on a
vendor's app or cloud to do it for you.

## Projects

| Device | Hubitat | Home Assistant | Homey |
|---|---|---|---|
| **SolarEdge** (inverter, meter, battery, EV charger) | [hubitat-solaredge](https://github.com/digital-homesteaders/hubitat-solaredge) | [ha-solaredge](https://github.com/digital-homesteaders/ha-solaredge) | |
| **Dreo** (fans, ceiling fans, humidifiers) | [hubitat-dreo](https://github.com/digital-homesteaders/hubitat-dreo) | | [homey-dreo](https://github.com/digital-homesteaders/homey-dreo) |

More are on the way. Browse by platform or brand with topics:
[hubitat](https://github.com/search?q=org%3Adigital-homesteaders+topic%3Ahubitat&type=repositories) ·
[home-assistant](https://github.com/search?q=org%3Adigital-homesteaders+topic%3Ahome-assistant&type=repositories) ·
[homey](https://github.com/search?q=org%3Adigital-homesteaders+topic%3Ahomey&type=repositories)

## Installing

- **Hubitat:** Hubitat Package Manager → *Install → From a URL*, with the `packageManifest.json` link in each project's README.
- **Home Assistant:** HACS → *Custom repositories*, type *Integration*.
- **Homey:** see each app's README.

## How we build

- **Tested on real hardware.** Each project's README or `TESTING.md` says what has been confirmed on a hub and what hasn't.
- **Gentle on your hub and the vendor's cloud.** Few requests, no needless polling, quiet logs.
- **Your data stays yours.** Passwords are never logged, and diagnostics leave out serials, MAC addresses and Wi-Fi names.
- **Credit where it's due.** Ports name the projects they come from and keep their licenses.

## Helping out

Bug reports, device logs and results from models we haven't tested are all welcome. Open an issue
on the project's repo. Pull requests are welcome too.

<sub>Not affiliated with or endorsed by Dreo, SolarEdge, Hubitat, Athom (Homey) or Home Assistant.
Brand names belong to their owners.</sub>
