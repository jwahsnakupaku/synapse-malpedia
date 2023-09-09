# Synapse-Malpedia
This Synapse Rapid Power-up adds support for ingesting [Malpedia](https://malpedia.caad.fkie.fraunhofer.de/) malware and threat actor profiles as well as related indicators and news reports.

---
## Usage
There are 5 commands available: 
- `ex.malpedia.ingest.actors`
    - Ingest all threat actor profiles from Malpedia
- `ex.malpedia.ingest.malware`
    - Ingest all malware profiles from Malpedia
- `ex.malpedia.ingest.indicators`
    - Ingest all indicators from Malpedia
- `ex.malpedia.setup.apikey`
    - Setup Malpedia API key (only needed for indicator ingest)
- `ex.malpedia.setup.tagprefix`
    - Setup Malpedia tag prefix

---
## Installation
The easiest way to use this Power-Up is to load the JSON package into the Cortex by running: 

`pkg.load --raw "https://raw.githubusercontent.com/EXC3L-ONE/synapse-malpedia/main/malpedia.json"`

Alternatively, you can also clone this repo, and load the package via `python -m synapse.tools.genpkg` (see reference in Synapse docs [here](https://synapse.docs.vertex.link/en/latest/synapse/userguides/syn_tools_genpkg.html#building-the-example-package))
