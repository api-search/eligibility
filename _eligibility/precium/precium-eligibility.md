---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organisation, you represent and warrant that you have the authority to bind that organisation to these Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted product categories
    text: All activities related to gambling, pornography, firearms, drugs, alcohol, marijuana, tobacco, and cryptocurrency related products and services are not permissible unless with express written permission from Precium.
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
name: Precium
provenance_date: '2026-11-10'
provider_name: Precium
provider_slug: precium
slug: precium-eligibility
source_date: '2026-11-10'
source_filename: precium-eligibility.yml
source_heading: Eligibility
source_page: https://www.precium.com/legal-docs/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Precium\naid: precium\nurl: https://www.precium.com/legal-docs/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organisation, you represent and warrant that you have the authority\n    to bind that organisation to these Terms\nrestricted_uses:\n- summary: Restricted product categories\n  text: All activities related to gambling, pornography, firearms, drugs, alcohol, marijuana, tobacco, and cryptocurrency\n    related products and services are not permissible unless with express\
  \ written permission from Precium.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/precium/eligibility/precium-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Precium's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Payments
- Payment Processing
- Payment Infrastructure
- Fintech
- South Africa
---
