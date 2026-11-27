---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be thirteen (13) years of age or older and reside in the United States or any of its territories to use the Services.
  entity_types:
  - text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity, and you represent and warrant that (a) you are an authorized representative of the entity
    type: individual
  minimum_age:
    text: You must be thirteen (13) years of age or older and reside in the United States or any of its territories to use the Services.
    value: '13'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: We hereby permit you to use the Services for your personal non-commercial use only
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
name: CG Oncology
provenance_date: '2026-11-09'
provider_name: CG Oncology
provider_slug: cg-oncology
slug: cg-oncology-eligibility
source_date: '2026-11-09'
source_filename: cg-oncology-eligibility.yml
source_heading: Eligibility
source_page: https://cgoncology.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CG Oncology\naid: cg-oncology\nurl: https://cgoncology.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be thirteen (13) years of age or older and reside in the United States or any of its territories\n    to use the Services.\nentity_types:\n- type: individual\n  text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity,\n    and you represent and warrant that (a) you are an authorized representative of the entity\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: We hereby\
  \ permit you to use the Services for your personal non-commercial use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be thirteen (13) years of age or older and reside in the United States or any of its territories\n    to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/cg-oncology/eligibility/cg-oncology-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CG Oncology's own page on 2026-11-09.
synthetic: false
tags:
- Oncology
- Bladder Cancer
- Immunotherapy
- Drug Development
---
