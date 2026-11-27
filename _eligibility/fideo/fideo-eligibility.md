---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site, Content, and Services are intended solely for persons who are 18 years of age or older.
    type: individual
  - text: if you represent an entity or other organization, that entity or organization (in either case, “you” or “your” )
    type: business
  minimum_age:
    text: The Site, Content, and Services are intended solely for persons who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: Fideo will permit you to access and use the Site solely for lawful purposes
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Approval of your request to establish an Account will be at our sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fideo
provenance_date: '2026-11-09'
provider_name: Fideo
provider_slug: fideo
slug: fideo-eligibility
source_date: '2026-11-09'
source_filename: fideo-eligibility.yml
source_heading: Eligibility
source_page: https://www.fideo.ai/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fideo\naid: fideo\nurl: https://www.fideo.ai/legal/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site, Content, and Services are intended solely for persons who are 18 years of age or older.\n- type: business\n  text: if you represent an entity or other organization, that entity or organization (in either case, “you” or\n    “your” )\nrestricted_uses:\n- summary: Lawful purposes only\n  text: Fideo will permit you to access and use the Site solely for lawful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ true\n  text: Approval of your request to establish an Account will be at our sole discretion.\nminimum_age:\n  value: '18'\n  text: The Site, Content, and Services are intended solely for persons who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/fideo/eligibility/fideo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Fideo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Identity Verification
- Fraud Prevention
- Identity Intelligence
- KYC
- AML
- Financial Crime
- Compliance
- Fintech
- Sanctions Screening
- Risk Scoring
---
