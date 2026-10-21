<p align="center">
  <img src="https://avatars.githubusercontent.com/u/345983678?s=160" width="96" alt="Digital Homesteaders icon">
</p>

<h1 align="center">Digital Homesteaders</h1>

<p align="center"><em>Your devices, your hub, your code.</em></p>

A homesteader grows their own food and lives off their own land. We bring that spirit to the smart
home: open-source drivers and apps that put your devices on the hub *you* run, so you're not left
waiting on a vendor's app or cloud.

## What we believe

- **Local first.** If a device can be controlled on your own network, that's how we talk to it.
  It's faster, it keeps working when the internet or the vendor's servers go down, and your data
  stays home. The cloud is the fallback, not the default.
- **Light on the cloud.** When a device only speaks through its vendor's cloud, we ask as little as
  we can: live updates instead of constant polling, no repeat requests, and backing off when the
  service says slow down. That keeps you clear of rate limits and lockouts, and keeps your hub
  running smoothly.
- **Tested on real hardware.** Every project says what has been confirmed on a real hub and what
  hasn't yet.
- **Your data stays yours.** Passwords are never logged, and diagnostics leave out serial numbers,
  MAC addresses and Wi-Fi names.
- **Credit where it's due.** Our ports name the projects they build on and keep their licenses.

## Built with AI, checked by people

We use AI coding assistants to move fast: a bug report or a new device can go from issue to fix in
days, not months. Every change still has to pass automated tests and run on a real hub before it's
released, and a person reviews it and stands behind it.

## Projects

| Device | Hubitat | Home Assistant |
|---|---|---|
| **SolarEdge** (inverter, meter, battery, EV charger) | [hubitat-solaredge](https://github.com/digital-homesteaders/hubitat-solaredge) | [ha-solaredge](https://github.com/digital-homesteaders/ha-solaredge) |
| **Dreo** (fans, ceiling fans, humidifiers) | [hubitat-dreo](https://github.com/digital-homesteaders/hubitat-dreo) | |
| **Govee** (lights, fans) | [hubitat-govee](https://github.com/digital-homesteaders/hubitat-govee) | |
| **ecobee** (thermostats, remote sensors) | [hubitat-ecobee](https://github.com/digital-homesteaders/hubitat-ecobee) | |

More are on the way, including Homey. Browse by platform:
[hubitat](https://github.com/search?q=org%3Adigital-homesteaders+topic%3Ahubitat&type=repositories) ·
[home-assistant](https://github.com/search?q=org%3Adigital-homesteaders+topic%3Ahome-assistant&type=repositories)

## Installing

- **Hubitat:** in Hubitat Package Manager, choose *Install → From a URL* and paste the
  `packageManifest.json` link from the project's README.
- **Home Assistant:** in HACS, add the repository under *Custom repositories* with type *Integration*.

## Helping out

Bug reports, device logs and results from models we haven't tested are all welcome. Open an issue
on the project's repo. Pull requests are welcome too.

<sub>Not affiliated with or endorsed by Dreo, SolarEdge, Govee, ecobee, Hubitat, Athom (Homey) or
Home Assistant. Brand names belong to their owners.</sub>
