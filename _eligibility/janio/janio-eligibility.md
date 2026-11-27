---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms on behalf of a company or other legal entity, you represent that you have the authority to bind such entity to these Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited shipment items
    text: You may not ship items that are prohibited by law or carrier policies
  verification:
    approval_required: null
    kyb: true
    kyc: null
    text: You must provide valid business registration documentation and tax identification numbers as required.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Janio
provenance_date: '2026-11-09'
provider_name: Janio
provider_slug: janio
slug: janio-eligibility
source_date: '2026-11-09'
source_filename: janio-eligibility.yml
source_heading: Eligibility
source_page: https://www.janio.asia/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Janio\naid: janio\nurl: https://www.janio.asia/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms on behalf of a company or other legal entity, you represent that you\n    have the authority to bind such entity to these Terms\nrestricted_uses:\n- summary: Prohibited shipment items\n  text: You may not ship items that are prohibited by law or carrier policies\nverification:\n  kyc: null\n  kyb: true\n  approval_required: null\n  text: You must provide valid business registration documentation and\
  \ tax identification numbers as required.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/janio/eligibility/janio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Janio's own page on 2026-11-09.
synthetic: false
tags:
- Logistics
- Supply Chain
- Shipping
- Fourth-Party Logistics
- Cross-border eCommerce
- Freight
- Tracking
- Southeast Asia
- Singapore
- Company
---
