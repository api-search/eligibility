---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Eat Just does not represent or warrant that the sites or any part thereof is appropriate or available for use in any particular jurisdiction other than the United States.
  entity_types:
  - text: Individuals under the age of 18 are not eligible to use these Sites and may not submit any personal information to us.
    type: individual
  minimum_age:
    text: By using these Sites, you hereby represent that you are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Fraudulent or unlawful use
    text: You may not use the Sites for any fraudulent or unlawful purpose
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
name: GOOD Meat
provenance_date: '2026-11-09'
provider_name: GOOD Meat
provider_slug: good-meat
slug: good-meat-eligibility
source_date: '2026-11-09'
source_filename: good-meat-eligibility.yml
source_heading: Eligibility
source_page: https://www.goodmeat.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GOOD Meat\naid: good-meat\nurl: https://www.goodmeat.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Eat Just does not represent or warrant that the sites or any part thereof is appropriate or available for\n    use in any particular jurisdiction other than the United States.\nentity_types:\n- type: individual\n  text: Individuals under the age of 18 are not eligible to use these Sites and may not submit any personal information\n    to us.\nrestricted_uses:\n- summary: Fraudulent or unlawful use\n  text: You may not use the Sites for any fraudulent or unlawful purpose\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using these Sites, you hereby represent that you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/good-meat/eligibility/good-meat-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from GOOD Meat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food and Beverage
- Cultivated Meat
- AgTech
- Consumer Packaged Goods
- Biotechnology
- Food Technology
- Sustainability
---
