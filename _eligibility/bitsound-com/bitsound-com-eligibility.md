---
api_specs:
- filename: bitsound-com-releases-api-openapi.yml
  format: yaml
  label: Bitsound Releases API
  slug: bitsound-com-releases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitsound-com/openapi/bitsound-com-releases-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - GB
    served: []
    text: We currently do not sell to buyers in the United Kingdom (Great Britain and Northern Ireland).
  entity_types:
  - text: A consumer within the meaning of these terms is anyone who concludes a transaction not for their business (§ 1 KSchG).
    type: individual
  - text: For businesses the place of jurisdiction is Bezirksgericht Vöcklabruck.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Minors needing guardian consent for paid orders
    text: If you are a minor and the consent of your legal guardian is required, you must obtain it before a paid order.
  - summary: No purchases from the United Kingdom
    text: If your country of residence, the country of your payment method or your location at the time of purchase points to the United Kingdom, a purchase is not possible.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The account is free. You need a valid email address that belongs to you.
excluded_countries:
- GB
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bitsound
provenance_date: '2026-11-09'
provider_name: Bitsound
provider_slug: bitsound-com
slug: bitsound-com-eligibility
source_date: '2026-11-09'
source_filename: bitsound-com-eligibility.yml
source_heading: Eligibility
source_page: https://bitsound.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bitsound\naid: bitsound-com\nurl: https://bitsound.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - GB\n  text: We currently do not sell to buyers in the United Kingdom (Great Britain and Northern Ireland).\nentity_types:\n- type: individual\n  text: A consumer within the meaning of these terms is anyone who concludes a transaction not for their business\n    (§ 1 KSchG).\n- type: business\n  text: For businesses the place of jurisdiction is Bezirksgericht Vöcklabruck.\nrestricted_uses:\n- summary: Minors needing guardian consent for paid orders\n  text: If you are a minor and\
  \ the consent of your legal guardian is required, you must obtain it before a paid\n    order.\n- summary: No purchases from the United Kingdom\n  text: If your country of residence, the country of your payment method or your location at the time of purchase\n    points to the United Kingdom, a purchase is not possible.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The account is free. You need a valid email address that belongs to you.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bitsound-com/eligibility/bitsound-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 6 quoted statements, read from Bitsound's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
