---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: We offer our AI solutions to adults (18 years of age or older) only.
    type: individual
  - text: If you are a health care provider, health plan employee, or other person or entity in the health care or medical industries who wishes to use our Services, you must enter into a separate services agreement with us.
    type: business
  minimum_age:
    text: You are an adult who is at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Illegal or abusive use
    text: Use the Site and/or Services for any illegal, unethical, abusive, offensive, harassing or unsolicited purpose
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
name: Ellipsis Health
provenance_date: '2026-11-09'
provider_name: Ellipsis Health
provider_slug: ellipsishealth
slug: ellipsishealth-eligibility
source_date: '2026-11-09'
source_filename: ellipsishealth-eligibility.yml
source_heading: Eligibility
source_page: https://ellipsishealth.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ellipsis Health\naid: ellipsishealth\nurl: https://ellipsishealth.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: We offer our AI solutions to adults (18 years of age or older) only.\n- type: business\n  text: If you are a health care provider, health plan employee, or other person or entity in the health care or\n    medical industries who wishes to use our Services, you must enter into a separate services agreement with us.\nrestricted_uses:\n- summary: Illegal or abusive use\n  text: Use the Site and/or Services\
  \ for any illegal, unethical, abusive, offensive, harassing or unsolicited purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are an adult who is at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/ellipsishealth/eligibility/ellipsishealth-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ellipsis Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Mental Health
- Artificial Intelligence
- Vocal Biomarkers
- Voice AI
- Digital Health
- Care Management
- HIPAA
---
