---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If Customer is using Mosaic products for personal, household consumer purposes in a jurisdiction that provides certain statutory remedies or warranties
    type: individual
  - text: If Customer is purchasing products for resale (as an authorized reseller), Customer must ensure the end-user agrees to Mosaic’s standard Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Mission-critical applications
    text: Products are not designed for use in mission-critical applications (e.g., life support or aerospace control systems) where failure could lead to severe harm, unless expressly agreed by Mosaic.
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
name: Mosaic Manufacturing
provenance_date: '2026-11-10'
provider_name: Mosaic Manufacturing
provider_slug: mosaicmanufacturing-com
slug: mosaicmanufacturing-com-eligibility
source_date: '2026-11-10'
source_filename: mosaicmanufacturing-com-eligibility.yml
source_heading: Eligibility
source_page: https://mosaicmfg.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mosaic Manufacturing\naid: mosaicmanufacturing-com\nurl: https://mosaicmfg.com/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If Customer is using Mosaic products for personal, household consumer purposes in a jurisdiction that provides\n    certain statutory remedies or warranties\n- type: business\n  text: If Customer is purchasing products for resale (as an authorized reseller), Customer must ensure the end-user\n    agrees to Mosaic’s standard Terms\nrestricted_uses:\n- summary: Mission-critical applications\n\
  \  text: Products are not designed for use in mission-critical applications (e.g., life support or aerospace control\n    systems) where failure could lead to severe harm, unless expressly agreed by Mosaic.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mosaicmanufacturing-com/eligibility/mosaicmanufacturing-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Mosaic Manufacturing's own page on 2026-11-10.
synthetic: false
tags:
- Company
- 3D Printing
- Manufacturing
- Industrial
---
