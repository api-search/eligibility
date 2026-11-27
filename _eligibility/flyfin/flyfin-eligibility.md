---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may not use any of the Services and you may not accept this Agreement if you are not legally authorized to accept and be bound by these terms or are not at least 18 years of age
    type: individual
  minimum_age:
    text: are not at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: You are only entitled to access and use the Sites and Services for lawful purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may verify your identity. You authorize us to make any inquiries we consider necessary to validate your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: FlyFin
provenance_date: '2026-11-09'
provider_name: FlyFin
provider_slug: flyfin
slug: flyfin-eligibility
source_date: '2026-11-09'
source_filename: flyfin-eligibility.yml
source_heading: Eligibility
source_page: https://flyfin.tax/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FlyFin\naid: flyfin\nurl: https://flyfin.tax/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may not use any of the Services and you may not accept this Agreement if you are not legally authorized\n    to accept and be bound by these terms or are not at least 18 years of age\nrestricted_uses:\n- summary: Lawful use only\n  text: You are only entitled to access and use the Sites and Services for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may verify your identity.\
  \ You authorize us to make any inquiries we consider necessary to validate your\n    identity.\nminimum_age:\n  value: '18'\n  text: are not at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/flyfin/eligibility/flyfin-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from FlyFin's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Tax
- Fintech
- Artificial Intelligence
- Accounting
- Freelance
- Self-Employed
---
