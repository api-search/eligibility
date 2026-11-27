---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'You may use the Website only if: You are legally capable of entering into a binding agreement; You are at least 18 years old'
    type: individual
  - text: If you access the Website on behalf of an organization, you represent that you are authorized to act on behalf of that organization.
    type: business
  minimum_age:
    text: You are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Unlawful, fraudulent or malicious use
    text: Use the Website for unlawful, fraudulent, deceptive, or malicious purposes
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
name: Sparkle
provenance_date: '2026-11-10'
provider_name: Sparkle
provider_slug: taai-labs-inc
slug: taai-labs-inc-eligibility
source_date: '2026-11-10'
source_filename: taai-labs-inc-eligibility.yml
source_heading: Eligibility
source_page: https://www.sparkle.security/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sparkle\naid: taai-labs-inc\nurl: https://www.sparkle.security/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'You may use the Website only if: You are legally capable of entering into a binding agreement; You are\n    at least 18 years old'\n- type: business\n  text: If you access the Website on behalf of an organization, you represent that you are authorized to act on\n    behalf of that organization.\nrestricted_uses:\n- summary: Unlawful, fraudulent or malicious use\n  text: Use the Website for unlawful, fraudulent, deceptive,\
  \ or malicious purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/taai-labs-inc/eligibility/taai-labs-inc-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Sparkle's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Application Security
- Artificial Intelligence
- Secure SDLC
- DevSecOps
- Agents
- Vulnerability Management
---
