---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: 'This website provides its services to the whole of India, subject to the following:'
  entity_types:
  - text: Transaction on the Platform is available only to persons who can form legally binding contracts under Indian Contract Act, 1872.
    type: individual
  - text: Select products offered by sellers may be eligible for business purchases on the Platform.
    type: business
  minimum_age:
    text: If you are a minor i.e. under the age of 18 years, you may use the Platform or access content on the Platform only under the supervision and prior consent/ permission of a parent or legal guardian.
    value: '18'
  restricted_uses:
  - summary: Tobacco purchases age limit
    text: You agree and undertake that You will not use the Platform to transact for the purchase of Tobacco products on the Platform if You are below the age of eighteen years (twenty one if ordering in the state of Karnataka).
  - summary: Prescription medicines require valid prescription
    text: No order for prescription medicine on the Flipkart website shall be or is being received without a valid Prescription.
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
name: Flipkart
provenance_date: '2026-11-09'
provider_name: Flipkart
provider_slug: flipkart
slug: flipkart-eligibility
source_date: '2026-11-09'
source_filename: flipkart-eligibility.yml
source_heading: Eligibility
source_page: https://www.flipkart.com/pages/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flipkart\naid: flipkart\nurl: https://www.flipkart.com/pages/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: 'This website provides its services to the whole of India, subject to the following:'\nentity_types:\n- type: individual\n  text: Transaction on the Platform is available only to persons who can form legally binding contracts under Indian\n    Contract Act, 1872.\n- type: business\n  text: Select products offered by sellers may be eligible for business purchases on the Platform.\nrestricted_uses:\n- summary: Tobacco purchases age limit\n  text:\
  \ You agree and undertake that You will not use the Platform to transact for the purchase of Tobacco products\n    on the Platform if You are below the age of eighteen years (twenty one if ordering in the state of Karnataka).\n- summary: Prescription medicines require valid prescription\n  text: No order for prescription medicine on the Flipkart website shall be or is being received without a valid\n    Prescription.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are a minor i.e. under the age of 18 years, you may use the Platform or access content on the Platform\n    only under the supervision and prior consent/ permission of a parent or legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/flipkart/eligibility/flipkart-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Flipkart's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- E-Commerce
- Marketplace
- Retail
- Sellers
- Order
- Fulfillment
- India
- OAuth
- Authentication
---
