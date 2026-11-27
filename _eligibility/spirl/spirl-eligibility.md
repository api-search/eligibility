---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: if you are a child under 16 years of age, please do not attempt to use the Website or send us any personal information.
    value: '16'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: violates any law or regulation, including, without limitation, any applicable export control laws, privacy laws
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
name: Spirl
provenance_date: '2026-11-10'
provider_name: Spirl
provider_slug: spirl
slug: spirl-eligibility
source_date: '2026-11-10'
source_filename: spirl-eligibility.yml
source_heading: Eligibility
source_page: https://www.defakto.security/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spirl\naid: spirl\nurl: https://www.defakto.security/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: violates any law or regulation, including, without limitation, any applicable export control laws, privacy\n    laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: if you are a child under 16 years of age, please do not attempt to use the Website or send us any personal\n    information.\n"
source_yaml_url: https://artifacts.apis.io/spirl/eligibility/spirl-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Spirl's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Identity
- Non-Human Identity
- Workload Identity
- SPIFFE
- Secrets Management
- Zero Trust
- CI/CD Security
- Kubernetes
- AI Agents
---
