---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Kalicart.com is for merchants.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Massive scraping for plagiarism
    text: The use of data for massive scraping aimed at plagiarism or unauthorized reproduction of merchant identity is strictly prohibited.
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
name: kalicart-com
provenance_date: '2026-11-09'
provider_name: kalicart-com
provider_slug: kalicart-com
slug: kalicart-com-eligibility
source_date: '2026-11-09'
source_filename: kalicart-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.kalicart.com/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: kalicart-com\naid: kalicart-com\nurl: https://www.kalicart.com/legal/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Kalicart.com is for merchants.\nrestricted_uses:\n- summary: Massive scraping for plagiarism\n  text: The use of data for massive scraping aimed at plagiarism or unauthorized reproduction of merchant identity\n    is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kalicart-com/eligibility/kalicart-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from kalicart-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- WooCommerce
- Agentic Commerce
- Open Protocol
- Artificial Intelligence
---
