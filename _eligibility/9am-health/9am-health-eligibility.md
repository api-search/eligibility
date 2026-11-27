---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are hosted in the United States and intended for use by residents of the United States.
  entity_types:
  - text: By accessing or using the Services, you represent to us that you are the age of 18 or older (or the age of majority in your jurisdiction, whichever is older)
    type: individual
  - text: If you are using the Services in connection with an employer or health plan's agreement with 9amHealth (an " Enterprise Agreement "), then you are an " Enterprise User, "
    type: business
  minimum_age:
    text: you are the age of 18 or older (or the age of majority in your jurisdiction, whichever is older)
    value: '18'
  restricted_uses:
  - summary: Not emergency care
    text: IF YOU THINK YOU MAY HAVE A MEDICAL EMERGENCY, CALL YOUR LOCAL EMERGENCY PHONE NUMBER OR DIAL 911
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
name: 9am Health
provenance_date: '2026-11-09'
provider_name: 9am Health
provider_slug: 9am-health
slug: 9am-health-eligibility
source_date: '2026-11-09'
source_filename: 9am-health-eligibility.yml
source_heading: Eligibility
source_page: https://join9am.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 9am Health\naid: 9am-health\nurl: https://join9am.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are hosted in the United States and intended for use by residents of the United States.\nentity_types:\n- type: individual\n  text: By accessing or using the Services, you represent to us that you are the age of 18 or older (or the age\n    of majority in your jurisdiction, whichever is older)\n- type: business\n  text: If you are using the Services in connection with an employer or health plan's agreement with 9amHealth (an\n    \" Enterprise Agreement\
  \ \"), then you are an \" Enterprise User, \"\nrestricted_uses:\n- summary: Not emergency care\n  text: IF YOU THINK YOU MAY HAVE A MEDICAL EMERGENCY, CALL YOUR LOCAL EMERGENCY PHONE NUMBER OR DIAL 911\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are the age of 18 or older (or the age of majority in your jurisdiction, whichever is older)\n"
source_yaml_url: https://artifacts.apis.io/9am-health/eligibility/9am-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from 9am Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Telehealth
- Digital Health
- Diabetes
- Metabolic Health
- Weight Loss
- Pharmacy
- Chronic Care
---
