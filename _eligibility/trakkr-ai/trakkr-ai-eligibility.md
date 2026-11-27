---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using Trakkr for a company, you confirm that you have the authority to bind that company to these terms.
    type: business
  minimum_age:
    text: You need to be at least 16 years old and capable of entering into a binding contract.
    value: '16'
  restricted_uses:
  - summary: Illegal activity
    text: Do not use Trakkr for anything illegal. This includes tracking brands you have no legitimate interest in
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
name: trakkr-ai
provenance_date: '2026-11-10'
provider_name: trakkr-ai
provider_slug: trakkr-ai
slug: trakkr-ai-eligibility
source_date: '2026-11-10'
source_filename: trakkr-ai-eligibility.yml
source_heading: Eligibility
source_page: https://trakkr.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: trakkr-ai\naid: trakkr-ai\nurl: https://trakkr.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using Trakkr for a company, you confirm that you have the authority to bind that company to these\n    terms.\nrestricted_uses:\n- summary: Illegal activity\n  text: Do not use Trakkr for anything illegal. This includes tracking brands you have no legitimate interest in\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You need to be at least 16 years\
  \ old and capable of entering into a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/trakkr-ai/eligibility/trakkr-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from trakkr-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Analytics
- Traffic
- Web
---
