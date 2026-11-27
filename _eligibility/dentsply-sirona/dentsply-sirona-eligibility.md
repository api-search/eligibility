---
api_specs:
- filename: dentsply-sirona-devices-api-openapi.yml
  format: yaml
  label: Dentsply Sirona Devices API
  slug: dentsply-sirona-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dentsply-sirona/openapi/dentsply-sirona-devices-api-openapi.yml
- filename: dentsply-sirona-exposures-api-openapi.yml
  format: yaml
  label: Dentsply Sirona Exposures API
  slug: dentsply-sirona-exposures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dentsply-sirona/openapi/dentsply-sirona-exposures-api-openapi.yml
- filename: dentsply-sirona-filters-api-openapi.yml
  format: yaml
  label: Dentsply Sirona Filters API
  slug: dentsply-sirona-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dentsply-sirona/openapi/dentsply-sirona-filters-api-openapi.yml
- filename: dentsply-sirona-generators-api-openapi.yml
  format: yaml
  label: Dentsply Sirona Generators API
  slug: dentsply-sirona-generators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dentsply-sirona/openapi/dentsply-sirona-generators-api-openapi.yml
- filename: dentsply-sirona-images-api-openapi.yml
  format: yaml
  label: Dentsply Sirona Images API
  slug: dentsply-sirona-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dentsply-sirona/openapi/dentsply-sirona-images-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded:
    - CU
    - KP
    - IR
    - SY
    served: []
    text: Desktop, mobile or other applications may not be downloaded or exported into (or to a national or resident of) Cuba, North Korea, Iran, Syria, and the Crimea region of Ukraine
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Adverse event reporting and medical emergencies
    text: The Site is not for medical emergencies. Do not use the Site for adverse event reporting.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- KP
- IR
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Dentsply Sirona
provenance_date: '2026-11-09'
provider_name: Dentsply Sirona
provider_slug: dentsply-sirona
slug: dentsply-sirona-eligibility
source_date: '2026-11-09'
source_filename: dentsply-sirona-eligibility.yml
source_heading: Eligibility
source_page: https://www.dentsplysirona.com/en-us/legal/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dentsply Sirona\naid: dentsply-sirona\nurl: https://www.dentsplysirona.com/en-us/legal/terms-of-use.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - KP\n  - IR\n  - SY\n  text: Desktop, mobile or other applications may not be downloaded or exported into (or to a national or resident\n    of) Cuba, North Korea, Iran, Syria, and the Crimea region of Ukraine\nentity_types: []\nrestricted_uses:\n- summary: Adverse event reporting and medical emergencies\n  text: The Site is not for medical emergencies. Do not use the Site for adverse event reporting.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dentsply-sirona/eligibility/dentsply-sirona-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Dentsply Sirona's own page on 2026-11-09.
synthetic: false
tags:
- CAD/CAM
- CEREC
- Dental
- DS Core
- Imaging
- Intraoral Imaging
- Lab Management
- Medical Devices
- Practice Management
- Fortune 1000
---
