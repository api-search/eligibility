---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you live elsewhere in the UK or in the EU, you keep the protection of mandatory consumer law where you live and may bring a claim there.
  entity_types:
  - text: One account per person.
    type: individual
  minimum_age:
    text: You must be 18 or over to buy a plan.
    value: '18'
  restricted_uses:
  - summary: Automated rebuilding of dataset
    text: don’t use automated means to rebuild it
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
name: All Paint Colours
provenance_date: '2026-11-09'
provider_name: All Paint Colours
provider_slug: allpaintcolours-co-uk
slug: allpaintcolours-co-uk-eligibility
source_date: '2026-11-09'
source_filename: allpaintcolours-co-uk-eligibility.yml
source_heading: Eligibility
source_page: https://allpaintcolours.co.uk/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: All Paint Colours\naid: allpaintcolours-co-uk\nurl: https://allpaintcolours.co.uk/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you live elsewhere in the UK or in the EU, you keep the protection of mandatory consumer law where you\n    live and may bring a claim there.\nentity_types:\n- type: individual\n  text: One account per person.\nrestricted_uses:\n- summary: Automated rebuilding of dataset\n  text: don’t use automated means to rebuild it\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must\
  \ be 18 or over to buy a plan.\n"
source_yaml_url: https://artifacts.apis.io/allpaintcolours-co-uk/eligibility/allpaintcolours-co-uk-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from All Paint Colours's own page on 2026-11-09.
synthetic: false
tags:
- Paint
- Colour
- United Kingdom
- Home Renovation
---
