---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for use by United States residents only. If you are a non-U.S. resident, you may access the Site solely at your own risk
  entity_types:
  - text: The Site is not intended for anyone under the age of 18.
    type: individual
  minimum_age:
    text: The Site is not intended for anyone under the age of 18.
    value: '18'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Upon our review and acceptance of your registration information, HistoSonics will provide you with a User ID and password.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HistoSonics
provenance_date: '2026-11-09'
provider_name: HistoSonics
provider_slug: histosonics
slug: histosonics-eligibility
source_date: '2026-11-09'
source_filename: histosonics-eligibility.yml
source_heading: Eligibility
source_page: https://histosonics.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HistoSonics\naid: histosonics\nurl: https://histosonics.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for use by United States residents only. If you are a non-U.S. resident, you may access\n    the Site solely at your own risk\nentity_types:\n- type: individual\n  text: The Site is not intended for anyone under the age of 18.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Upon our review and acceptance of your registration information, HistoSonics will provide you with a User\n    ID\
  \ and password.\nminimum_age:\n  value: '18'\n  text: The Site is not intended for anyone under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/histosonics/eligibility/histosonics-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from HistoSonics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Medical Devices
- Healthcare
- Health Tech
- Oncology
- Focused Ultrasound
- Surgical Robotics
- Medical Imaging
---
