# Airtouch 2+ integration

_Component to integrate with Polyaire Airtouch 2+._

Utilizes [airtouch2-python](https://github.com/nathanvdh/airtouch2-python)

**This component will set up the following platforms.**

Platform | Description
-- | --
`climate` | Control temperature, mode, fan speed

## Installation

1. In the HA UI go to HACS and Add Repository as a custom repository "Click ..." -> "Custom Repositories" -> Enter "https://github.com/nathanvdh/homeassistant-airtouch2plus" and type "Integration" -> Save
1. Search of "airtouch2plus" in HACS and install
1. In the HA UI go to "Configuration" -> "Integrations" click "+" and search for "airtouch2plus".
1. Enter the host address (IP) of the Airtouch 2+ system
