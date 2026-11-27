---
api_specs:
- filename: usagerail-openapi-generated.yml
  format: yaml
  label: UsageRail API
  slug: usagerail-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usagerail/openapi/_ae-authored/usagerail-openapi-generated.yml
claim_count: 1
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
  - summary: Phishing, spam, malware, fraud, illegal use
    text: Don't use UsageRail, or a portal it hosts, for phishing, spam, malware, fraud or anything illegal where you or your customers are.
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
name: UsageRail
provenance_date: '2026-11-10'
provider_name: UsageRail
provider_slug: usagerail
slug: usagerail-eligibility
source_date: '2026-11-10'
source_filename: usagerail-eligibility.yml
source_heading: Eligibility
source_page: https://usagerail.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UsageRail\naid: usagerail\nurl: https://usagerail.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Phishing, spam, malware, fraud, illegal use\n  text: Don't use UsageRail, or a portal it hosts, for phishing, spam, malware, fraud or anything illegal where\n    you or your customers are.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/usagerail/eligibility/usagerail-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from UsageRail's own page on 2026-11-10.
synthetic: false
tags:
- Company
- API Monetization
- Software-as-a-Service
- Billing
- Rate Limiting
- Developer Tools
---
