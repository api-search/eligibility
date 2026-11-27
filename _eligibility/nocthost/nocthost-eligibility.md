---
api_specs:
- filename: nocthost-openapi-generated.yml
  format: yaml
  label: NoctHost API
  slug: nocthost-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nocthost/openapi/_ae-authored/nocthost-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Abuse and prohibited activity
    text: Spam, phishing, malware or C2, botnets, DDoS attacks, and CSAM are prohibited and lead to termination.
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: We do not currently perform Know-Your-Customer (KYC) checks, and identity verification is not part of signing up or using the service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: NoctHost
provenance_date: '2026-11-10'
provider_name: NoctHost
provider_slug: nocthost
slug: nocthost-eligibility
source_date: '2026-11-10'
source_filename: nocthost-eligibility.yml
source_heading: Eligibility
source_page: https://nocthost.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NoctHost\naid: nocthost\nurl: https://nocthost.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Abuse and prohibited activity\n  text: Spam, phishing, malware or C2, botnets, DDoS attacks, and CSAM are prohibited and lead to termination.\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: We do not currently perform Know-Your-Customer (KYC) checks, and identity verification is not part of signing\n    up or using the service.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nocthost/eligibility/nocthost-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from NoctHost's own page on 2026-11-10.
synthetic: false
tags:
- Company
- VPS
- Cloud
- Crypto Payments
- GPU
---
