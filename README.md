# Menpo

## Overview

DeFi Incidents in STIX 2.1.

## Using Python to generate STIX objects

### Installing

```bash
cd scripts
python3 -m venv menpo_env
source menpo_env/bin/activate
pip3 install -r requirements.txt
```

### Creating a bundle

```bash
cd scripts
source menpo_env/bin/activate

python3 <stix2 python script>
```

Example

```bash
cd scripts
source menpo_env/bin/activate

python3 22.09.01.kyberswap.py
```
## Visualization of incidents

Suppose you created and wrapped the STIX objects of your incident into the file `stix-db/22.09.01.kyberswap.json`.

To visualize the incident, just use [Oasis' CTI STIX Visualizer](https://oasis-open.github.io/cti-stix-visualization/) this way:

https://oasis-open.github.io/cti-stix-visualization/?url=https://raw.githubusercontent.com/bentobox19/menpo-napier/blob/main/stix-db/22.09.01.kyberswap.json

<img width="888" alt="Visualization 00" src="https://user-images.githubusercontent.com/85324266/232174604-41c2ba3b-57dd-4c10-975d-5845b7dbf5ef.png">
