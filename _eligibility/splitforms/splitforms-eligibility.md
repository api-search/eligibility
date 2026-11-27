---
api_specs:
- filename: splitforms-openapi.json
  format: json
  label: Form Submission API
  slug: form-submission-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/splitforms/openapi/splitforms-openapi.json
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
  - summary: Regulated data (HIPAA, PCI-DSS)
    text: collect data subject to specific legal regimes (HIPAA, PCI-DSS) without explicit prior agreement
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
name: Split Forms
provenance_date: '2026-11-10'
provider_name: Split Forms
provider_slug: splitforms
slug: splitforms-eligibility
source_date: '2026-11-10'
source_filename: splitforms-eligibility.yml
source_heading: Eligibility
source_page: https://splitforms.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Split Forms\naid: splitforms\nurl: https://splitforms.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Regulated data (HIPAA, PCI-DSS)\n  text: collect data subject to specific legal regimes (HIPAA, PCI-DSS) without explicit prior agreement\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/splitforms/eligibility/splitforms-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Split Forms's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Form Backend
- Developer Tools
- Free Tier
- Webhook
---
