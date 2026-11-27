---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Kate Farms currently ships only to locations within the 50 United States.
  entity_types:
  - text: By accessing or using any Services via a mobile device, you agree to these Terms
    type: individual
  - source: https://katefarms.com/policy/terms-of-use/
    text: By accessing, using and/or submitting information to or through the Services, you represent that you are at least age 16.
    type: individual
  minimum_age:
    text: YOU MUST BE AT LEAST AGE 16 TO ACCESS AND USE THE SERVICES.
    value: '16'
  restricted_uses:
  - summary: no resale or bulk/dealer orders
    text: We reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers, resellers or distributors.
  - source: https://katefarms.com/policy/terms-of-use/
    summary: Purchases limited to personal use
    text: Products purchased from us are for personal use only or as a gift and are not for resale.
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
name: Kate Farms
provenance_date: '2026-11-09'
provider_name: Kate Farms
provider_slug: kate-farms
slug: kate-farms-eligibility
source_date: '2026-11-09'
source_filename: kate-farms-eligibility.yml
source_heading: Eligibility
source_page: https://shop.katefarms.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kate Farms\naid: kate-farms\nurl: https://shop.katefarms.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://katefarms.com/policy/terms-of-use/\n  - https://shop.katefarms.com/policies/terms-of-service\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Kate Farms currently ships only to locations within the 50 United States.\nentity_types:\n- type: individual\n  text: By accessing or using any Services via a mobile device, you agree to these Terms\n- type: individual\n  text: By accessing, using and/or submitting information to or through the Services, you represent that you\
  \ are\n    at least age 16.\n  source: https://katefarms.com/policy/terms-of-use/\nrestricted_uses:\n- summary: no resale or bulk/dealer orders\n  text: We reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers,\n    resellers or distributors.\n- summary: Purchases limited to personal use\n  text: Products purchased from us are for personal use only or as a gift and are not for resale.\n  source: https://katefarms.com/policy/terms-of-use/\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: YOU MUST BE AT LEAST AGE 16 TO ACCESS AND USE THE SERVICES.\n"
source_yaml_url: https://artifacts.apis.io/kate-farms/eligibility/kate-farms-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Kate Farms's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Nutrition
- Medical Nutrition
- Health
- Food and Beverage
- Consumer Packaged Goods
- E-Commerce
- Agentic Commerce
- Retail
- Shopify
- GraphQL
---
