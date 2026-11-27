---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: be a temporary or permanent resident of a province or territory of Canada
  entity_types:
  - text: 'In order to open an account to use the Maple Platform (" M-Account "), you must: be at least 18 years of age'
    type: individual
  minimum_age:
    text: be at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Not for emergencies
    text: THE MAPLE PLATFORM CANNOT BE USED FOR EMERGENCY HEALTHCARE.
  - summary: Personal use only
    text: you will use the Maple Platform solely for your personal and non-commercial use
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: nothing in these Terms requires Maple to accept any registrant as a User, notwithstanding that the registrant meets Maple's eligibility requirements as amended from time to time
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Maple
provenance_date: '2026-11-10'
provider_name: Maple
provider_slug: maple-health
slug: maple-health-eligibility
source_date: '2026-11-10'
source_filename: maple-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.getmaple.ca/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Maple\naid: maple-health\nurl: https://www.getmaple.ca/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: be a temporary or permanent resident of a province or territory of Canada\nentity_types:\n- type: individual\n  text: 'In order to open an account to use the Maple Platform (\" M-Account \"), you must: be at least 18 years of\n    age'\nrestricted_uses:\n- summary: Not for emergencies\n  text: THE MAPLE PLATFORM CANNOT BE USED FOR EMERGENCY HEALTHCARE.\n- summary: Personal use only\n  text: you will use the Maple Platform solely for your personal and non-commercial use\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: nothing in these Terms requires Maple to accept any registrant as a User, notwithstanding that the registrant\n    meets Maple's eligibility requirements as amended from time to time\nminimum_age:\n  value: '18'\n  text: be at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/maple-health/eligibility/maple-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Maple's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- Canada
- Telehealth
- Virtual Care
- Digital Health
- Mental Health
- e-Prescribing
- Remote Care
---
