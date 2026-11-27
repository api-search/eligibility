---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Unless otherwise specified, the Service is presented solely for residents of United States of America.
  entity_types:
  - text: This Service is intended for individuals who are at least 13 years old.
    type: individual
  minimum_age:
    text: This Service is intended for individuals who are at least 13 years old. If you are under the age of 13 years old, you may not use this Service.
    value: '13'
  restricted_uses:
  - summary: Unlawful use prohibited
    text: Use the Service for any purpose that is prohibited by any law or regulation, or to facilitate the violation of any law or regulation;
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
name: CenterPoint Energy
provenance_date: '2026-11-09'
provider_name: CenterPoint Energy
provider_slug: centerpoint-energy
slug: centerpoint-energy-eligibility
source_date: '2026-11-09'
source_filename: centerpoint-energy-eligibility.yml
source_heading: Eligibility
source_page: https://www.centerpointenergy.com/en-us/about-us/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CenterPoint Energy\naid: centerpoint-energy\nurl: https://www.centerpointenergy.com/en-us/about-us/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Unless otherwise specified, the Service is presented solely for residents of United States of America.\nentity_types:\n- type: individual\n  text: This Service is intended for individuals who are at least 13 years old.\nrestricted_uses:\n- summary: Unlawful use prohibited\n  text: Use the Service for any purpose that is prohibited by any law or regulation, or to facilitate the violation\n    of any law or regulation;\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: This Service is intended for individuals who are at least 13 years old. If you are under the age of 13 years\n    old, you may not use this Service.\n"
source_yaml_url: https://artifacts.apis.io/centerpoint-energy/eligibility/centerpoint-energy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CenterPoint Energy's own page on 2026-11-09.
synthetic: false
tags:
- EDI
- ERCOT
- Electricity
- Energy
- Fortune 500
- Green Button
- Interval Data
- NAESB ESPI
- Natural Gas
- Smart Meter
- Texas
- TxSET
- Usage Data
- Utility
---
