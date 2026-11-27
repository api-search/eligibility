---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Sites is controlled and operated from within the United States. We make no representation that the Sites or Services ... complies with the laws of any foreign jurisdictions.
  entity_types:
  - text: Any use of or access to the Site or Services by anyone under 18 is not permitted and violates these Terms.
    type: individual
  minimum_age:
    text: you represent and warrant that you are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful content
    text: upload, post, transmit, share, store or otherwise make available any material that (i) contains software viruses
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
name: CarSaver
provenance_date: '2026-11-09'
provider_name: CarSaver
provider_slug: carsaver
slug: carsaver-eligibility
source_date: '2026-11-09'
source_filename: carsaver-eligibility.yml
source_heading: Eligibility
source_page: https://www.carsaver.ai/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CarSaver\naid: carsaver\nurl: https://www.carsaver.ai/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Sites is controlled and operated from within the United States. We make no representation that the Sites\n    or Services ... complies with the laws of any foreign jurisdictions.\nentity_types:\n- type: individual\n  text: Any use of or access to the Site or Services by anyone under 18 is not permitted and violates these Terms.\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: upload, post, transmit, share, store or otherwise make available\
  \ any material that (i) contains software\n    viruses\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/carsaver/eligibility/carsaver-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CarSaver's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Automotive
- Fintech
- Marketplace
- Car Buying
---
