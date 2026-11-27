---
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
  - summary: Export controls and military end use
    text: Customer represents and warrants that (i) the Customer will not use Walnut’s Platform to capture a solution that is subject to any export licensing requirements under applicable export control laws
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
name: Walnut
provenance_date: '2026-11-10'
provider_name: Walnut
provider_slug: walnut
slug: walnut-eligibility
source_date: '2026-11-10'
source_filename: walnut-eligibility.yml
source_heading: Eligibility
source_page: https://www.walnut.io/msa/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Walnut\naid: walnut\nurl: https://www.walnut.io/msa/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export controls and military end use\n  text: Customer represents and warrants that (i) the Customer will not use Walnut’s Platform to capture a solution\n    that is subject to any export licensing requirements under applicable export control laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/walnut/eligibility/walnut-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Walnut's own page on 2026-11-10.
synthetic: false
tags:
- Sales Demo
- Interactive Demos
- Product Demos
- Sales Enablement
- Demo Analytics
- Go-To-Market
- Webhook
- MCP
- Analytics
---
