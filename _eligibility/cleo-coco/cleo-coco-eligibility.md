---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are at least 18 years old or visiting this Site under the supervision of a parent or guardian.
    type: individual
  minimum_age:
    text: You represent and warrant that you are at least 18 years old or visiting this Site under the supervision of a parent or guardian.
    value: '18'
  restricted_uses:
  - summary: Orders restricted by jurisdiction
    text: We reserve the right to refuse or cancel any orders placed for products and/or services which the sale or use of such product and/or service in your state or jurisdiction is restricted or prohibited.
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
name: Cleo+Coco
provenance_date: '2026-11-09'
provider_name: Cleo+Coco
provider_slug: cleo-coco
slug: cleo-coco-eligibility
source_date: '2026-11-09'
source_filename: cleo-coco-eligibility.yml
source_heading: Eligibility
source_page: https://cleoandcoco.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cleo+Coco\naid: cleo-coco\nurl: https://cleoandcoco.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least 18 years old or visiting this Site under the supervision\n    of a parent or guardian.\nrestricted_uses:\n- summary: Orders restricted by jurisdiction\n  text: We reserve the right to refuse or cancel any orders placed for products and/or services which the sale or\n    use of such product and/or service in your state or jurisdiction is restricted or prohibited.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least 18 years old or visiting this Site under the supervision\n    of a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/cleo-coco/eligibility/cleo-coco-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Cleo+Coco's own page on 2026-11-09.
synthetic: false
tags:
- Deodorant
- Personal Care
- Body Powder
- Functional Spray
- Clean Beauty
---
