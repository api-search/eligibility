---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - KZ
    text: by territory – within the territory of the Republic of Kazakhstan and other countries where the Licensor officially provides services;
  entity_types:
  - text: an individual, sole proprietor or legal entity that has accepted this Agreement
    type: individual
  - text: an individual, sole proprietor or legal entity that has accepted this Agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful purposes
    text: use the Program for purposes that violate the laws of the Republic of Kazakhstan
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Verified individual account (Account) – an account in the Program corresponding to a specific individual who has been granted access to the Program and who has been verified by means of an SMS code, email, biometric identification device or other methods
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Clockster
provenance_date: '2026-11-09'
provider_name: Clockster
provider_slug: clockster
slug: clockster-eligibility
source_date: '2026-11-09'
source_filename: clockster-eligibility.yml
source_heading: Eligibility
source_page: https://app.clockster.com/terms-and-conditions?locale=en
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clockster\naid: clockster\nurl: https://app.clockster.com/terms-and-conditions?locale=en\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - KZ\n  excluded: []\n  text: by territory – within the territory of the Republic of Kazakhstan and other countries where the Licensor\n    officially provides services;\nentity_types:\n- type: individual\n  text: an individual, sole proprietor or legal entity that has accepted this Agreement\n- type: business\n  text: an individual, sole proprietor or legal entity that has accepted this Agreement\nrestricted_uses:\n- summary: Unlawful purposes\n  text: use the Program\
  \ for purposes that violate the laws of the Republic of Kazakhstan\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Verified individual account (Account) – an account in the Program corresponding to a specific individual\n    who has been granted access to the Program and who has been verified by means of an SMS code, email, biometric\n    identification device or other methods\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clockster/eligibility/clockster-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Clockster's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Human Resources
- Workforce Management
- Time Tracking
- Attendance
- Payroll
- Scheduling
- Staff Management
- Retail
- Food and Beverage
- Software-as-a-Service
---
