---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are responsible for complying with all laws and regulations in the country in which you live when you access and use the Services.
  entity_types:
  - text: If you decide to initiate arbitration on behalf of the company or legal entity you represent
    type: business
  minimum_age:
    text: The Services are not intended for users under 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Commercial advertising or spam
    text: Is commercial in nature, including but not limited to spam, surveys, contests, pyramid schemes, or other advertising materials
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
name: Adentro
provenance_date: '2026-11-09'
provider_name: Adentro
provider_slug: adentro
slug: adentro-eligibility
source_date: '2026-11-09'
source_filename: adentro-eligibility.yml
source_heading: Eligibility
source_page: https://adentro.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Adentro\naid: adentro\nurl: https://adentro.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are responsible for complying with all laws and regulations in the country in which you live when you\n    access and use the Services.\nentity_types:\n- type: business\n  text: If you decide to initiate arbitration on behalf of the company or legal entity you represent\nrestricted_uses:\n- summary: Commercial advertising or spam\n  text: Is commercial in nature, including but not limited to spam, surveys, contests, pyramid schemes, or other\n    advertising materials\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are not intended for users under 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/adentro/eligibility/adentro-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Adentro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Ai Apps
- WiFi Marketing
- Customer Intelligence
- Location Analytics
- Retail
- Marketing Attribution
- Guest WiFi
---
