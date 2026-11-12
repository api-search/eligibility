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
  - summary: Unauthorised Cloudflare accounts
    text: use Controlflare on a Cloudflare account you are not authorised to manage
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
name: Controlflare
provenance_date: '2026-11-09'
provider_name: Controlflare
provider_slug: controlflare-com
slug: controlflare-com-eligibility
source_date: '2026-11-09'
source_filename: controlflare-com-eligibility.yml
source_heading: Eligibility
source_page: https://controlflare.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Controlflare\naid: controlflare-com\nurl: https://controlflare.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unauthorised Cloudflare accounts\n  text: use Controlflare on a Cloudflare account you are not authorised to manage\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/controlflare-com/eligibility/controlflare-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Controlflare's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloudflare
- Cloudflare Workers
- Cost Management
- Budget Caps
- FinOps
- MCP
- Model Context Protocol
- Serverless
---
