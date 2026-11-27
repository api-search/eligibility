---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the term “Supplier” means the Supplier, Contractor, or Vendor listed on the applicable Purchase Order
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No obtaining unintended materials
    text: You may not obtain, or try to obtain, any materials or information that is not intentionally made available on the Champion site.
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
name: Champion Iron
provenance_date: '2026-11-09'
provider_name: Champion Iron
provider_slug: champion-iron
slug: champion-iron-eligibility
source_date: '2026-11-09'
source_filename: champion-iron-eligibility.yml
source_heading: Eligibility
source_page: https://www.championiron.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Champion Iron\naid: champion-iron\nurl: https://www.championiron.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the term “Supplier” means the Supplier, Contractor, or Vendor listed on the applicable Purchase Order\nrestricted_uses:\n- summary: No obtaining unintended materials\n  text: You may not obtain, or try to obtain, any materials or information that is not intentionally made available\n    on the Champion site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/champion-iron/eligibility/champion-iron-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Champion Iron's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mining
- Iron Ore
- Metals
- Natural Resources
- Steel Supply Chain
- Canada
- Australia
---
