---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: You must be at least 18 years of age and an Australian resident or have a dispute subject to Australian law to use Claim Done.
  minimum_age:
    text: You must be at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Electronic signing limits
    text: Claim Done Sign must not be used for a deed, will, affidavit, statutory declaration, court form or any document requiring a witness, prescribed execution process or independent legal advice.
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
name: Claim Done
provenance_date: '2026-11-09'
provider_name: Claim Done
provider_slug: claimdone-com-au
slug: claimdone-com-au-eligibility
source_date: '2026-11-09'
source_filename: claimdone-com-au-eligibility.yml
source_heading: Eligibility
source_page: https://claimdone.com.au/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Claim Done\naid: claimdone-com-au\nurl: https://claimdone.com.au/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: You must be at least 18 years of age and an Australian resident or have a dispute subject to Australian\n    law to use Claim Done.\nentity_types: []\nrestricted_uses:\n- summary: Electronic signing limits\n  text: Claim Done Sign must not be used for a deed, will, affidavit, statutory declaration, court form or any document\n    requiring a witness, prescribed execution process or independent legal advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/claimdone-com-au/eligibility/claimdone-com-au-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Claim Done's own page on 2026-11-09.
synthetic: false
tags:
- Legal Tech
- Australia
- Document Automation
- Software-as-a-Service
- Small Business
---
