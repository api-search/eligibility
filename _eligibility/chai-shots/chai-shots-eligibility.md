---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: You are residing in and using this Application from within India.
  entity_types:
  - text: The services offered by the App are intended for individuals who have reached the age of majority in the Territory
    type: individual
  minimum_age:
    text: The services offered by the App are intended for individuals who have reached the age of majority in the Territory
    value: age of majority
  restricted_uses:
  - summary: Personal non-commercial use only
    text: solely for personal, non-commercial entertainment purposes through the App only in accordance with these Terms of Use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Your registration shall be verified via a one-time password (OTP) sent to Your mobile number
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Chai Shots
provenance_date: '2026-11-09'
provider_name: Chai Shots
provider_slug: chai-shots
slug: chai-shots-eligibility
source_date: '2026-11-09'
source_filename: chai-shots-eligibility.yml
source_heading: Eligibility
source_page: https://chaishots.in/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chai Shots\naid: chai-shots\nurl: https://chaishots.in/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: You are residing in and using this Application from within India.\nentity_types:\n- type: individual\n  text: The services offered by the App are intended for individuals who have reached the age of majority in the\n    Territory\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: solely for personal, non-commercial entertainment purposes through the App only in accordance with these\n    Terms of Use.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: Your registration shall be verified via a one-time password (OTP) sent to Your mobile number\nminimum_age:\n  value: age of majority\n  text: The services offered by the App are intended for individuals who have reached the age of majority in the\n    Territory\n"
source_yaml_url: https://artifacts.apis.io/chai-shots/eligibility/chai-shots-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Chai Shots's own page on 2026-11-09.
synthetic: false
tags:
- Company
- OTT
- Streaming
- Entertainment
- Video
- Microdrama
- Consumer
- India
---
