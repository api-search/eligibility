---
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
  - summary: Violating law in API access
    text: access our APIs or documentation in violation of any law or regulation
  - summary: Testing system vulnerabilities
    text: tests the vulnerability of our systems or networks
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
name: APIwiz
provenance_date: '2026-11-09'
provider_name: APIwiz
provider_slug: apiwiz
slug: apiwiz-eligibility
source_date: '2026-11-09'
source_filename: apiwiz-eligibility.yml
source_heading: Eligibility
source_page: https://www.apiwiz.io/legal/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: APIwiz\naid: apiwiz\nurl: https://www.apiwiz.io/legal/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Violating law in API access\n  text: access our APIs or documentation in violation of any law or regulation\n- summary: Testing system vulnerabilities\n  text: tests the vulnerability of our systems or networks\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apiwiz/eligibility/apiwiz-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from APIwiz's own page on 2026-11-09.
synthetic: false
tags:
- API Design
- API Gateway
- API Governance
- API Lifecycle
- API Management
- API Monetization
- API Security
- Automation
- Developer Tools
- Low-Code
- Observability
- Platform
---
