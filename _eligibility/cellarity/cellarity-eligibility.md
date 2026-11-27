---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must ... reside in the United States or any of its territories to use our Website.
  entity_types:
  - text: If you use the Website on behalf of a company or other entity, then “you” includes you and that entity, and you represent and warrant that (a) you are an authorized representative of such entity
    type: business
  minimum_age:
    text: You must be 18 years of age or older and reside in the United States or any of its territories to use our Website.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: you will not export or re-export, directly or indirectly, the Website and/or other information or materials provided by Cellarity hereunder, to any country for which the United States or any other relevant jurisdiction requires any export license
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
name: Cellarity
provenance_date: '2026-11-09'
provider_name: Cellarity
provider_slug: cellarity
slug: cellarity-eligibility
source_date: '2026-11-09'
source_filename: cellarity-eligibility.yml
source_heading: Eligibility
source_page: https://cellarity.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cellarity\naid: cellarity\nurl: https://cellarity.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must ... reside in the United States or any of its territories to use our Website.\nentity_types:\n- type: business\n  text: If you use the Website on behalf of a company or other entity, then “you” includes you and that entity,\n    and you represent and warrant that (a) you are an authorized representative of such entity\nrestricted_uses:\n- summary: Export restrictions\n  text: you will not export or re-export, directly or indirectly, the Website and/or\
  \ other information or materials\n    provided by Cellarity hereunder, to any country for which the United States or any other relevant jurisdiction\n    requires any export license\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older and reside in the United States or any of its territories to use our\n    Website.\n"
source_yaml_url: https://artifacts.apis.io/cellarity/eligibility/cellarity-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cellarity's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Drug Discovery
- Life Sciences
- Artificial Intelligence
- Machine Learning
- Single Cell
- Transcriptomics
- Pharmaceuticals
- Clinical Trials
- Hematology
- Research
- Content
---
