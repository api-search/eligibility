---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you, if registering as an individual
    type: individual
  - text: the entity you represent if registering as a business
    type: business
  minimum_age:
    text: You are of majority age and have the full right, power, and authority to enter into and fully perform this Agreement.
    value: null
  restricted_uses:
  - summary: No unlawful use
    text: You may not use the API in any manner or for any purpose that violates any law or regulation
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
name: Spark Platform
provenance_date: '2026-11-10'
provider_name: Spark Platform
provider_slug: spark-platform
slug: spark-platform-eligibility
source_date: '2026-11-10'
source_filename: spark-platform-eligibility.yml
source_heading: Eligibility
source_page: https://sparkplatform.com/docs/terms_of_use/developer_agreement_and_terms_of_use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spark Platform\naid: spark-platform\nurl: https://sparkplatform.com/docs/terms_of_use/developer_agreement_and_terms_of_use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you, if registering as an individual\n- type: business\n  text: the entity you represent if registering as a business\nrestricted_uses:\n- summary: No unlawful use\n  text: You may not use the API in any manner or for any purpose that violates any law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: You are of majority age and have the full right, power, and authority to enter into and fully perform this\n    Agreement.\n"
source_yaml_url: https://artifacts.apis.io/spark-platform/eligibility/spark-platform-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Spark Platform's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- United States
- MLS
- RESO
- Property Listings
- IDX
- PropTech
- Listing Data Infrastructure
- OData
---
