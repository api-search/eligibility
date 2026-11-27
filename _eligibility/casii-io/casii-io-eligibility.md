---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Casii works with WhatsApp accounts that belong to you or your organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age of legal majority where you live, to create an account or purchase a subscription.
    value: '18'
  restricted_uses:
  - summary: Harassment, fraud, malware
    text: Use the service for harassment, threats, fraud, misleading claims or distribution of malware
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
name: Casii
provenance_date: '2026-11-09'
provider_name: Casii
provider_slug: casii-io
slug: casii-io-eligibility
source_date: '2026-11-09'
source_filename: casii-io-eligibility.yml
source_heading: Eligibility
source_page: https://casii.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Casii\naid: casii-io\nurl: https://casii.io/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Casii works with WhatsApp accounts that belong to you or your organization.\nrestricted_uses:\n- summary: Harassment, fraud, malware\n  text: Use the service for harassment, threats, fraud, misleading claims or distribution of malware\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of legal majority where you live, to create\
  \ an account or\n    purchase a subscription.\n"
source_yaml_url: https://artifacts.apis.io/casii-io/eligibility/casii-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Casii's own page on 2026-11-09.
synthetic: false
tags:
- Sales
- Lead Management
- Multilingual
- Outreach
- Prospecting
---
