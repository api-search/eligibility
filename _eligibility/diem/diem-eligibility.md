---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Diem provides the Service from the United States, and the Service is designed for Members who are residents of the United States.
  entity_types:
  - text: Membership to Diem for individuals is free
    type: individual
  minimum_age:
    text: You must be at least 18 years old to register and use the Service.
    value: '18'
  restricted_uses:
  - summary: Not for emergency medical situations
    text: THE SERVICE IS NOT INTENDED FOR EMERGENCY MEDICAL SITUATIONS.
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
name: Diem
provenance_date: '2026-11-09'
provider_name: Diem
provider_slug: diem
slug: diem-eligibility
source_date: '2026-11-09'
source_filename: diem-eligibility.yml
source_heading: Eligibility
source_page: https://www.askdiem.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Diem\naid: diem\nurl: https://www.askdiem.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Diem provides the Service from the United States, and the Service is designed for Members who are residents\n    of the United States.\nentity_types:\n- type: individual\n  text: Membership to Diem for individuals is free\nrestricted_uses:\n- summary: Not for emergency medical situations\n  text: THE SERVICE IS NOT INTENDED FOR EMERGENCY MEDICAL SITUATIONS.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: You must be at least 18 years old to register and use the Service.\n"
source_yaml_url: https://artifacts.apis.io/diem/eligibility/diem-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Diem's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Social
- Search
- Community
- Consumer
- Mobile App
- Women
---
