---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - GB
    - CA
    - BR
    - IE
    - DE
    - IN
    text: Only residents of the United States, Europe (only in countries where offered), the United Kingdom, Canada, Brazil, Puerto Rico, Ireland, Germany and India are eligible to access and use the Services.
  entity_types:
  - text: Services are available only at the individual user level and are not permitted for use by commercial or business accounts.
    type: business
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE PLATFORM OR ACCEPT THESE TERMS IF YOU ARE NOT AT LEAST THE AGE OF MAJORITY IN YOUR JURISDICTION OF RESIDENCE.
    value: age of majority
  restricted_uses:
  - summary: No prescribing of Schedule I-V drugs without in-person exam
    text: When a VCPR is formed by audio-visual means rather than an in-person physical exam, AIRVET prohibits the prescribing of Schedule I through V drugs as listed by the United States Drug Enforcement Administration or compounded medications.
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
name: Airvet
provenance_date: '2026-11-09'
provider_name: Airvet
provider_slug: airvet
slug: airvet-eligibility
source_date: '2026-11-09'
source_filename: airvet-eligibility.yml
source_heading: Eligibility
source_page: https://airvet.com/pet-parents-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Airvet\naid: airvet\nurl: https://airvet.com/pet-parents-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - GB\n  - CA\n  - BR\n  - IE\n  - DE\n  - IN\n  excluded: []\n  text: Only residents of the United States, Europe (only in countries where offered), the United Kingdom, Canada,\n    Brazil, Puerto Rico, Ireland, Germany and India are eligible to access and use the Services.\nentity_types:\n- type: business\n  text: Services are available only at the individual user level and are not permitted for use by commercial or\n    business accounts.\nrestricted_uses:\n- summary: No prescribing\
  \ of Schedule I-V drugs without in-person exam\n  text: When a VCPR is formed by audio-visual means rather than an in-person physical exam, AIRVET prohibits the\n    prescribing of Schedule I through V drugs as listed by the United States Drug Enforcement Administration or\n    compounded medications.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: YOU MAY NOT ACCESS OR USE THE PLATFORM OR ACCEPT THESE TERMS IF YOU ARE NOT AT LEAST THE AGE OF MAJORITY\n    IN YOUR JURISDICTION OF RESIDENCE.\n"
source_yaml_url: https://artifacts.apis.io/airvet/eligibility/airvet-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Airvet's own page on 2026-11-09.
synthetic: false
tags:
- Pet Care
- Veterinary
- Telehealth
- Employee Benefits
- Health
- Mobile App
- Pets
- Company
---
