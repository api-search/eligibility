---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If your billing address is in an EU country, you must be buying as a business and enter a valid EU VAT number from that same country at checkout.
  entity_types:
  - text: Instilus sells to businesses. By buying, you confirm you are buying for the purposes of your trade or business.
    type: business
  - text: If you are nonetheless a consumer, nothing in these terms affects the rights the law gives you as a consumer.
    type: individual
  minimum_age:
    text: null
    value: null
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
name: instilus-com
provenance_date: '2026-11-09'
provider_name: instilus-com
provider_slug: instilus-com
slug: instilus-com-eligibility
source_date: '2026-11-09'
source_filename: instilus-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.instilus.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: instilus-com\naid: instilus-com\nurl: https://www.instilus.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If your billing address is in an EU country, you must be buying as a business and enter a valid EU VAT number\n    from that same country at checkout.\nentity_types:\n- type: business\n  text: Instilus sells to businesses. By buying, you confirm you are buying for the purposes of your trade or business.\n- type: individual\n  text: If you are nonetheless a consumer, nothing in these terms affects the rights the law gives you as a consumer.\nrestricted_uses: []\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/instilus-com/eligibility/instilus-com-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 3 quoted statements, read from instilus-com's own page on 2026-11-09.
synthetic: false
tags:
- E-Commerce
- Valuation
- Shopify
- Tools
- Finance
---
