---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Buyers and Sellers must be over the age of 18 when buying or selling any Item through the VarageSale Platform.
    type: individual
  - text: Any small business creating an account must provide the full name of the proprietor/owner, not just a business name.
    type: business
  minimum_age:
    text: Members under 18 are not permitted.
    value: '18'
  restricted_uses:
  - summary: Prohibited items
    text: VarageSale prohibits the sale of a number of items, such as firearms, regulated products and services and illegal goods and services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to build a strong trusted community of people, we ask that you provide your real name or an identifying name when creating a VarageSale account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Varagesale
provenance_date: '2026-11-10'
provider_name: Varagesale
provider_slug: varagesale
slug: varagesale-eligibility
source_date: '2026-11-10'
source_filename: varagesale-eligibility.yml
source_heading: Eligibility
source_page: https://www.varagesale.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Varagesale\naid: varagesale\nurl: https://www.varagesale.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Buyers and Sellers must be over the age of 18 when buying or selling any Item through the VarageSale Platform.\n- type: business\n  text: Any small business creating an account must provide the full name of the proprietor/owner, not just a business\n    name.\nrestricted_uses:\n- summary: Prohibited items\n  text: VarageSale prohibits the sale of a number of items, such as firearms, regulated products and services\
  \ and\n    illegal goods and services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to build a strong trusted community of people, we ask that you provide your real name or an identifying\n    name when creating a VarageSale account.\nminimum_age:\n  value: '18'\n  text: Members under 18 are not permitted.\n"
source_yaml_url: https://artifacts.apis.io/varagesale/eligibility/varagesale-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Varagesale's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Marketplace
- Classifieds
- Local Commerce
- Secondhand
- Mobile App
---
