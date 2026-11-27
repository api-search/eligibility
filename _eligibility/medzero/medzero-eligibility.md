---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age or the legal age of majority in your jurisdiction to use the Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age or the legal age of majority in your jurisdiction to use the Services.
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: Services may be used only as permitted by law and regulations.
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
name: MedZero
provenance_date: '2026-11-10'
provider_name: MedZero
provider_slug: medzero
slug: medzero-eligibility
source_date: '2026-11-10'
source_filename: medzero-eligibility.yml
source_heading: Eligibility
source_page: https://medzero.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MedZero\naid: medzero\nurl: https://medzero.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age or the legal age of majority in your jurisdiction to use the Services.\nrestricted_uses:\n- summary: Lawful use only\n  text: Services may be used only as permitted by law and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age or the legal age of majority in your jurisdiction\
  \ to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/medzero/eligibility/medzero-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from MedZero's own page on 2026-11-10.
synthetic: false
tags:
- healthcare-financing
- Employee Benefits
- Financial Wellness
- Spending Account
- Employer Benefits
---
