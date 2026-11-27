---
api_specs:
- filename: doc.yaml
  format: yaml
  label: Sigfox Cloud API
  slug: sigfox-cloud-api
  spec_type: OpenAPI
  url: https://api.sigfox.com/v2/doc.yaml
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
  - summary: Unlawful use
    text: You may not use the Sigfox Website in any way that violates any applicable local, national, or international law or regulation
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
name: Sigfox
provenance_date: '2026-11-10'
provider_name: Sigfox
provider_slug: sigfox
slug: sigfox-eligibility
source_date: '2026-11-10'
source_filename: sigfox-eligibility.yml
source_heading: Eligibility
source_page: https://sigfox.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sigfox\naid: sigfox\nurl: https://sigfox.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use\n  text: You may not use the Sigfox Website in any way that violates any applicable local, national, or international\n    law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sigfox/eligibility/sigfox-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Sigfox's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Industrial, Energy & Iot
- IoT
- LPWAN
- Connectivity
- Device Management
- Networking
- Telecommunications
---
