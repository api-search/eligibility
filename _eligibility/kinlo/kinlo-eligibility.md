---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Products displayed on the Site can be ordered and delivered only within the United States.
  entity_types:
  - text: We further reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers, resellers or distributors.
    type: business
  minimum_age:
    text: You represent and warrant that you are at least 13 years of age. If you are under age 13, you may not, under any circumstances or for any reason, use the Site.
    value: '13'
  restricted_uses:
  - summary: Resale of products
    text: You may not sell or resell any of the Products, or samples thereof, you purchase or otherwise receive from us.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may take steps to verify your identity to process your order and may limit or cancel quantities of Products purchased per person, per household or per order.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kinlo
provenance_date: '2026-11-09'
provider_name: Kinlo
provider_slug: kinlo
slug: kinlo-eligibility
source_date: '2026-11-09'
source_filename: kinlo-eligibility.yml
source_heading: Eligibility
source_page: https://www.kinlo.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kinlo\naid: kinlo\nurl: https://www.kinlo.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Products displayed on the Site can be ordered and delivered only within the United States.\nentity_types:\n- type: business\n  text: We further reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed\n    by dealers, resellers or distributors.\nrestricted_uses:\n- summary: Resale of products\n  text: You may not sell or resell any of the Products, or samples thereof, you purchase or otherwise receive from\n    us.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may take steps to verify your identity to process your order and may limit or cancel quantities of Products\n    purchased per person, per household or per order.\nminimum_age:\n  value: '13'\n  text: You represent and warrant that you are at least 13 years of age. If you are under age 13, you may not, under\n    any circumstances or for any reason, use the Site.\n"
source_yaml_url: https://artifacts.apis.io/kinlo/eligibility/kinlo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Kinlo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Skincare
- Suncare
- Beauty
- SPF
- E-Commerce
- Direct to Consumer
---
