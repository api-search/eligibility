---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: We do not knowingly collect or solicit personally identifiable information from children under 16 years of age
    value: '16'
  restricted_uses:
  - summary: Unlawful, harmful or abusive use
    text: violates any law or regulation, including, without limitation, any applicable export control laws, privacy laws or any other purpose not reasonably intended by Defakto Security
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
name: Defakto Security
provenance_date: '2026-11-09'
provider_name: Defakto Security
provider_slug: defakto-security
slug: defakto-security-eligibility
source_date: '2026-11-09'
source_filename: defakto-security-eligibility.yml
source_heading: Eligibility
source_page: https://www.defakto.security/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Defakto Security\naid: defakto-security\nurl: https://www.defakto.security/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful, harmful or abusive use\n  text: violates any law or regulation, including, without limitation, any applicable export control laws, privacy\n    laws or any other purpose not reasonably intended by Defakto Security\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: We do not knowingly collect or solicit personally identifiable\
  \ information from children under 16 years\n    of age\n"
source_yaml_url: https://artifacts.apis.io/defakto-security/eligibility/defakto-security-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Defakto Security's own page on 2026-11-09.
synthetic: false
tags:
- Security
- Identity
- Non-Human Identity
- Workload Identity
- SPIFFE
- Authentication
- Zero Trust
- Secrets Management
- Kubernetes
- CI/CD
- Cloud Security
- gRPC
- Machine Identity
- AI Agents
- Developer Tools
- Identity Federation
---
