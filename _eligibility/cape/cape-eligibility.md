---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Subscriber may activate Cape’s Services only where the Services are offered and supported by Cape.
  entity_types:
  - text: you must be at least 18 years old to use our service
    type: individual
  minimum_age:
    text: you must be at least 18 years old to use our service
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
name: Cape
provenance_date: '2026-11-09'
provider_name: Cape
provider_slug: cape
slug: cape-eligibility
source_date: '2026-11-09'
source_filename: cape-eligibility.yml
source_heading: Eligibility
source_page: https://www.cape.co/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cape\naid: cape\nurl: https://www.cape.co/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Subscriber may activate Cape’s Services only where the Services are offered and supported by Cape.\nentity_types:\n- type: individual\n  text: you must be at least 18 years old to use our service\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old to use our service\n"
source_yaml_url: https://artifacts.apis.io/cape/eligibility/cape-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Cape's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Privacy
- Mobile
- Telecommunications
- Carrier
- MVNO
- Security
- Consumer
---
