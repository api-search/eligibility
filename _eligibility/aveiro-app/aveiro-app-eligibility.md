---
api_specs:
- filename: aveiro-app-openapi-generated.yml
  format: yaml
  label: Aveiro API
  slug: aveiro-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aveiro-app/openapi/_ae-authored/aveiro-app-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18, or the age of majority where you live.
    type: individual
  - text: If you use a service for a company or other organisation, you accept them for that organisation and confirm you may do so.
    type: business
  minimum_age:
    text: You must be at least 18, or the age of majority where you live.
    value: '18'
  restricted_uses:
  - summary: Unlawful or abusive use
    text: break the law, or help someone else break it; infringe intellectual property, privacy or other rights of others; send spam, malware, phishing or misleading content
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: During the closed beta, signup may need an invite code or waitlist approval, and we may change those rules.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aveiro
provenance_date: '2026-11-09'
provider_name: Aveiro
provider_slug: aveiro-app
slug: aveiro-app-eligibility
source_date: '2026-11-09'
source_filename: aveiro-app-eligibility.yml
source_heading: Eligibility
source_page: https://www.aveiro.app/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aveiro\naid: aveiro-app\nurl: https://www.aveiro.app/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18, or the age of majority where you live.\n- type: business\n  text: If you use a service for a company or other organisation, you accept them for that organisation and confirm\n    you may do so.\nrestricted_uses:\n- summary: Unlawful or abusive use\n  text: break the law, or help someone else break it; infringe intellectual property, privacy or other rights of\n    others; send spam, malware, phishing\
  \ or misleading content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: During the closed beta, signup may need an invite code or waitlist approval, and we may change those rules.\nminimum_age:\n  value: '18'\n  text: You must be at least 18, or the age of majority where you live.\n"
source_yaml_url: https://artifacts.apis.io/aveiro-app/eligibility/aveiro-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Aveiro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- No-Code
- Publishing
- Templates
- Artificial Intelligence
---
