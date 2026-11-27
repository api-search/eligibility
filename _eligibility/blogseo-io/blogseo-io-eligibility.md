---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you (a) are at least 18 years old and legally capable of entering into contracts
    type: individual
  - text: use the Service for your internal business purposes
    type: business
  minimum_age:
    text: you represent that you (a) are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Illegal, deceptive or fraudulent use
    text: use the Service for any illegal, deceptive, or fraudulent purpose
  - summary: Direct competitors
    text: use the Service if you are a direct competitor, or for competitive analysis, benchmarking, or to develop a competing product
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
name: BlogSEO
provenance_date: '2026-11-09'
provider_name: BlogSEO
provider_slug: blogseo-io
slug: blogseo-io-eligibility
source_date: '2026-11-09'
source_filename: blogseo-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.blogseo.io/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BlogSEO\naid: blogseo-io\nurl: https://www.blogseo.io/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you (a) are at least 18 years old and legally capable of entering into contracts\n- type: business\n  text: use the Service for your internal business purposes\nrestricted_uses:\n- summary: Illegal, deceptive or fraudulent use\n  text: use the Service for any illegal, deceptive, or fraudulent purpose\n- summary: Direct competitors\n  text: use the Service if you are a direct competitor, or for competitive analysis, benchmarking,\
  \ or to develop\n    a competing product\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent that you (a) are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/blogseo-io/eligibility/blogseo-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from BlogSEO's own page on 2026-11-09.
synthetic: false
tags:
- SEO
- Artificial Intelligence
- Content Generation
- Marketing
- Automation
---
