# hassio-bluetti-bt
[![hacs_badge](https://img.shields.io/badge/HACS-Default-41BDF5.svg)](https://github.com/hacs/integration)
[![Validate with hassfest](https://github.com/Patrick762/hassio-bluetti-bt/actions/workflows/hassfest_validation.yml/badge.svg)](https://github.com/Patrick762/hassio-bluetti-bt/actions/workflows/hassfest_validation.yml)
[![HACS Action](https://github.com/Patrick762/hassio-bluetti-bt/actions/workflows/HACS.yml/badge.svg)](https://github.com/Patrick762/hassio-bluetti-bt/actions/workflows/HACS.yml)

Bluetti Integration for Home Assistant

> **This is a fork** of [Patrick762/hassio-bluetti-bt](https://github.com/Patrick762/hassio-bluetti-bt) that adds the BLUETTI FridgePower (`FP`).
> It installs [bluetti-bt-lib](https://github.com/rgw3d/bluetti-bt-lib/tree/add-fridgepower-support) from the `add-fridgepower-support` branch until
> [Patrick762/bluetti-bt-lib#106](https://github.com/Patrick762/bluetti-bt-lib/pull/106) is released. Use the upstream integration for everything else.
>
> To install: HACS > three-dot menu > Custom repositories > add `https://github.com/rgw3d/hassio-bluetti-bt` with type "Integration".
> The FridgePower is an encrypted device, so its controls show up read-only (as sensors and binary sensors), like every other encrypted device in this integration.

The current [Roadmap for this project and the library can be found here](https://github.com/users/Patrick762/projects/4)

## Disclaimer
This integration is provided without any warranty or support by Bluetti. I do not take responsibility for any problems it may cause in all cases. Use it at your own risk.

## Installation
To install this integration, you first need [HACS](https://hacs.xyz/) installed.
After the installation, you can use this button to install the integration:

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=Patrick762&repository=hassio-bluetti-bt&category=integration)

### Supported devices:

See [bluetti-bt-lib](https://github.com/Patrick762/bluetti-bt-lib?tab=readme-ov-file#supported-powerstations-and-data)

### Available controls:
See [bluetti-bt-lib](https://github.com/Patrick762/bluetti-bt-lib?tab=readme-ov-file#supported-powerstations-and-data)

### Adding devices or fields

Please use the issue template at [bluetti-bt-lib](https://github.com/Patrick762/bluetti-bt-lib?tab=readme-ov-file#supported-powerstations-and-data)
