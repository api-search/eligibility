---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Access to and use of the Platform is available only to individuals who are at least 18 years old and can form legally binding contracts under applicable law.
    type: individual
  - text: If you use the Platform on behalf of an entity, you represent and warrant that you have the authority to bind that entity
    type: business
  minimum_age:
    text: at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Commercial use of Free Services
    text: Use Free Services forecasts, data, or analytics for commercial purposes without prior written approval from NCX
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
name: NCX
provenance_date: '2026-11-10'
provider_name: NCX
provider_slug: ncx
slug: ncx-eligibility
source_date: '2026-11-10'
source_filename: ncx-eligibility.yml
source_heading: Eligibility
source_page: https://ncx.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NCX\naid: ncx\nurl: https://ncx.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Access to and use of the Platform is available only to individuals who are at least 18 years old and can\n    form legally binding contracts under applicable law.\n- type: business\n  text: If you use the Platform on behalf of an entity, you represent and warrant that you have the authority to\n    bind that entity\nrestricted_uses:\n- summary: Commercial use of Free Services\n  text: Use Free Services forecasts, data, or analytics for commercial\
  \ purposes without prior written approval from\n    NCX\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/ncx/eligibility/ncx-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from NCX's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Forestry
- Carbon
- Land
- Sustainability
- Climate
- Natural Capital
- Geospatial
---
