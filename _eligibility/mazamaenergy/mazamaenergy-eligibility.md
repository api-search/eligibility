---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Sites are not intended for use by children under age 18 (or the age of majority in your jurisdiction if it is greater than age 18).
    type: individual
  - text: If you are an individual accessing or using the Sites on behalf of, or for the benefit of any entity with which you are associated (an “Organization”), then you are agreeing to these Terms on behalf of yourself and such Organization
    type: business
  minimum_age:
    text: By using the Sites, you represent and warrant that you are at least 18 years of age (or the age of majority in your jurisdiction).
    value: '18'
  restricted_uses:
  - summary: Competitor or benchmarking access
    text: If you are a competitor, or for purposes of monitoring the Sites’ availability, performance or functionality, or for any other benchmarking or competitive purposes.
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
name: Mazama Energy
provenance_date: '2026-11-10'
provider_name: Mazama Energy
provider_slug: mazamaenergy
slug: mazamaenergy-eligibility
source_date: '2026-11-10'
source_filename: mazamaenergy-eligibility.yml
source_heading: Eligibility
source_page: https://mazamaenergy.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mazama Energy\naid: mazamaenergy\nurl: https://mazamaenergy.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Sites are not intended for use by children under age 18 (or the age of majority in your jurisdiction\n    if it is greater than age 18).\n- type: business\n  text: If you are an individual accessing or using the Sites on behalf of, or for the benefit of any entity with\n    which you are associated (an “Organization”), then you are agreeing to these Terms on behalf of yourself and\n    such Organization\n\
  restricted_uses:\n- summary: Competitor or benchmarking access\n  text: If you are a competitor, or for purposes of monitoring the Sites’ availability, performance or functionality,\n    or for any other benchmarking or competitive purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the Sites, you represent and warrant that you are at least 18 years of age (or the age of majority\n    in your jurisdiction).\n"
source_yaml_url: https://artifacts.apis.io/mazamaenergy/eligibility/mazamaenergy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Mazama Energy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Energy
- Geothermal
- Clean Energy
- Renewable Energy
- Enhanced Geothermal Systems
- Power Generation
- Climate Tech
---
