---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: an individual or business that has created an account online and accepted these terms by checking the acceptance box at signup ("Self-Serve Customer")
    type: individual
  - text: a business that has entered into an Order Form with Remy AI that references this Agreement ("Enterprise Customer")
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful, fraudulent, or competitive purpose
    text: (d) not use the Platform for any unlawful, fraudulent, or competitive purpose.
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
name: Nomad Homes
provenance_date: '2026-11-10'
provider_name: Nomad Homes
provider_slug: nomad-homes
slug: nomad-homes-eligibility
source_date: '2026-11-10'
source_filename: nomad-homes-eligibility.yml
source_heading: Eligibility
source_page: https://www.getremy.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nomad Homes\naid: nomad-homes\nurl: https://www.getremy.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: an individual or business that has created an account online and accepted these terms by checking the acceptance\n    box at signup (\"Self-Serve Customer\")\n- type: business\n  text: a business that has entered into an Order Form with Remy AI that references this Agreement (\"Enterprise\n    Customer\")\nrestricted_uses:\n- summary: Unlawful, fraudulent, or competitive purpose\n  text: (d) not use the Platform for any\
  \ unlawful, fraudulent, or competitive purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nomad-homes/eligibility/nomad-homes-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Nomad Homes's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Real Estate
- PropTech
- Artificial Intelligence
- AI Assistant
- Productivity
---
