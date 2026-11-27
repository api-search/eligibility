---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Business accounts for commercial AI Agent deployment require additional verification including business registration, tax identification, and compliance documentation.
    type: business
  minimum_age:
    text: You must be at least 18 years old to create monetized AI Agents
    value: '18'
  restricted_uses:
  - summary: Industry-specific restrictions
    text: 'Additional restrictions apply to AI Agents used in: Healthcare: Medical advice, diagnosis, or treatment recommendations'
  verification:
    approval_required: null
    kyb: true
    kyc: null
    text: Business accounts for commercial AI Agent deployment require additional verification including business registration, tax identification, and compliance documentation.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kuverto
provenance_date: '2026-11-09'
provider_name: Kuverto
provider_slug: kuverto
slug: kuverto-eligibility
source_date: '2026-11-09'
source_filename: kuverto-eligibility.yml
source_heading: Eligibility
source_page: https://kuverto.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kuverto\naid: kuverto\nurl: https://kuverto.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Business accounts for commercial AI Agent deployment require additional verification including business\n    registration, tax identification, and compliance documentation.\nrestricted_uses:\n- summary: Industry-specific restrictions\n  text: 'Additional restrictions apply to AI Agents used in: Healthcare: Medical advice, diagnosis, or treatment\n    recommendations'\nverification:\n  kyc: null\n  kyb: true\n  approval_required: null\n\
  \  text: Business accounts for commercial AI Agent deployment require additional verification including business\n    registration, tax identification, and compliance documentation.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create monetized AI Agents\n"
source_yaml_url: https://artifacts.apis.io/kuverto/eligibility/kuverto-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Kuverto's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- No-Code
- Platform
- Automation
- Agents
- Integration
---
