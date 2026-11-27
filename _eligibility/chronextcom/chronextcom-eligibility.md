---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If the Customer is a consumer (i.e. a natural person who places the order
    type: individual
  - text: The GTC apply regardless of whether the Customer is a consumer or an entrepreneur.
    type: business
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
name: Chronextcom
provenance_date: '2026-11-09'
provider_name: Chronextcom
provider_slug: chronextcom
slug: chronextcom-eligibility
source_date: '2026-11-09'
source_filename: chronextcom-eligibility.yml
source_heading: Eligibility
source_page: https://www.chronext.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chronextcom\naid: chronextcom\nurl: https://www.chronext.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If the Customer is a consumer (i.e. a natural person who places the order\n- type: business\n  text: The GTC apply regardless of whether the Customer is a consumer or an entrepreneur.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chronextcom/eligibility/chronextcom-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Chronextcom's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Luxury
- Watches
- E-Commerce
- Germany
---
