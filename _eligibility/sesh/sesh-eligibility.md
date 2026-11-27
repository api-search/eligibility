---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: SALE ONLY ALLOWED IN THE UNITED STATES.
  entity_types:
  - text: The Website is for the exclusive use of adult consumers, who have reached legal age in their jurisdiction of residence to purchase our products.
    type: individual
  - text: We reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers, resellers or distributors.
    type: business
  minimum_age:
    text: you acknowledge and certify that you are at least 21 years of age.
    value: '21'
  restricted_uses:
  - summary: Use by under-age persons
    text: The use of the Website by persons who are not of legal age to purchase our products in their jurisdiction of residence is strictly forbidden.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Age will be verified prior to purchase and at the time of accessing the site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sesh
provenance_date: '2026-11-10'
provider_name: Sesh
provider_slug: sesh
slug: sesh-eligibility
source_date: '2026-11-10'
source_filename: sesh-eligibility.yml
source_heading: Eligibility
source_page: https://seshproducts.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sesh\naid: sesh\nurl: https://seshproducts.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: SALE ONLY ALLOWED IN THE UNITED STATES.\nentity_types:\n- type: individual\n  text: The Website is for the exclusive use of adult consumers, who have reached legal age in their jurisdiction\n    of residence to purchase our products.\n- type: business\n  text: We reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers,\n    resellers or distributors.\nrestricted_uses:\n- summary: Use by under-age persons\n \
  \ text: The use of the Website by persons who are not of legal age to purchase our products in their jurisdiction\n    of residence is strictly forbidden.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Age will be verified prior to purchase and at the time of accessing the site.\nminimum_age:\n  value: '21'\n  text: you acknowledge and certify that you are at least 21 years of age.\n"
source_yaml_url: https://artifacts.apis.io/sesh/eligibility/sesh-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Sesh's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer Packaged Goods
- Nicotine Pouches
- E-Commerce
- Direct to Consumer
- Retail
- Subscription
---
