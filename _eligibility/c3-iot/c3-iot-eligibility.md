---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may not access or use the site or accept the terms if you are not at least 18 years old.
    type: individual
  - text: By accessing or using the site, you are accepting these terms (on behalf of yourself or the entity that you represent)
    type: business
  minimum_age:
    text: You may not access or use the site or accept the terms if you are not at least 18 years old.
    value: '18'
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
name: C3.ai (C3 IoT)
provenance_date: '2026-11-09'
provider_name: C3.ai (C3 IoT)
provider_slug: c3-iot
slug: c3-iot-eligibility
source_date: '2026-11-09'
source_filename: c3-iot-eligibility.yml
source_heading: Eligibility
source_page: https://www.c3.ai/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: C3.ai (C3 IoT)\naid: c3-iot\nurl: https://www.c3.ai/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may not access or use the site or accept the terms if you are not at least 18 years old.\n- type: business\n  text: By accessing or using the site, you are accepting these terms (on behalf of yourself or the entity that\n    you represent)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may not access or use the site\
  \ or accept the terms if you are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/c3-iot/eligibility/c3-iot-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from C3.ai (C3 IoT)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Enterprise
- Platform
- IoT
- Industry
---
