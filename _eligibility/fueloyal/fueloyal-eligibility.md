---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No use while driving
    text: The Applications should not be used while operating a vehicle.
  - summary: No unlawful, misleading, malicious or discriminatory use
    text: use the Applications to do anything unlawful, misleading, malicious, or discriminatory
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fueloyal
provenance_date: '2026-11-09'
provider_name: Fueloyal
provider_slug: fueloyal
slug: fueloyal-eligibility
source_date: '2026-11-09'
source_filename: fueloyal-eligibility.yml
source_heading: Eligibility
source_page: https://www.fueloyal.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fueloyal\naid: fueloyal\nurl: https://www.fueloyal.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No use while driving\n  text: The Applications should not be used while operating a vehicle.\n- summary: No unlawful, misleading, malicious or discriminatory use\n  text: use the Applications to do anything unlawful, misleading, malicious, or discriminatory\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fueloyal/eligibility/fueloyal-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Fueloyal's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fleet Management
- Connected Vehicles
- IoT
- Automotive
- Fuel Management
- Telematics
- Predictive Maintenance
- Electric Vehicles
---
