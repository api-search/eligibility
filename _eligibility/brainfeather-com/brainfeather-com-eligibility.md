---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old to use Brainfeather.
    type: individual
  - text: If you are agreeing on behalf of a company, you confirm you have the authority to bind that company, and “you” means the company.
    type: business
  minimum_age:
    text: You must be at least 16 years old to use Brainfeather.
    value: '16'
  restricted_uses:
  - summary: Unlawful or unlicensed content
    text: Store or process material you have no right to hold — including someone else's confidential information or personal data you have no lawful basis for.
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
name: Brainfeather
provenance_date: '2026-11-09'
provider_name: Brainfeather
provider_slug: brainfeather-com
slug: brainfeather-com-eligibility
source_date: '2026-11-09'
source_filename: brainfeather-com-eligibility.yml
source_heading: Eligibility
source_page: https://brainfeather.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brainfeather\naid: brainfeather-com\nurl: https://brainfeather.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old to use Brainfeather.\n- type: business\n  text: If you are agreeing on behalf of a company, you confirm you have the authority to bind that company, and\n    “you” means the company.\nrestricted_uses:\n- summary: Unlawful or unlicensed content\n  text: Store or process material you have no right to hold — including someone else's confidential information\n    or personal data you\
  \ have no lawful basis for.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use Brainfeather.\n"
source_yaml_url: https://artifacts.apis.io/brainfeather-com/eligibility/brainfeather-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Brainfeather's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Memory
- Agents
- MCP
- Beta
---
