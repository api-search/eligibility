---
api_specs:
- filename: versori-platform-openapi.yml
  format: yaml
  label: Versori Platform API
  slug: versori-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/versori/openapi/versori-platform-openapi.yml
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
  - summary: Fraudulent or unlawful use
    text: use the Versori Switchboard Platform for any fraudulent or unlawful purpose
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
name: Versori
provenance_date: '2026-11-10'
provider_name: Versori
provider_slug: versori
slug: versori-eligibility
source_date: '2026-11-10'
source_filename: versori-eligibility.yml
source_heading: Eligibility
source_page: https://www.versori.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Versori\naid: versori\nurl: https://www.versori.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Fraudulent or unlawful use\n  text: use the Versori Switchboard Platform for any fraudulent or unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/versori/eligibility/versori-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Versori's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Integration
- Artificial Intelligence
- Automation
- Platform
---
