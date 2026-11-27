---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be old enough to agree to these terms where you live, and at least 13.
    type: individual
  - text: If you use the service for a company, you accept them for that company too.
    type: business
  minimum_age:
    text: You must be old enough to agree to these terms where you live, and at least 13.
    value: '13'
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
name: CheapCADTools
provenance_date: '2026-11-09'
provider_name: CheapCADTools
provider_slug: cheapcadtools-com
slug: cheapcadtools-com-eligibility
source_date: '2026-11-09'
source_filename: cheapcadtools-com-eligibility.yml
source_heading: Eligibility
source_page: https://cheapcadtools.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CheapCADTools\naid: cheapcadtools-com\nurl: https://cheapcadtools.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be old enough to agree to these terms where you live, and at least 13.\n- type: business\n  text: If you use the service for a company, you accept them for that company too.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be old enough to agree to these terms where you live, and at least 13.\n"
source_yaml_url: https://artifacts.apis.io/cheapcadtools-com/eligibility/cheapcadtools-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from CheapCADTools's own page on 2026-11-09.
synthetic: false
tags:
- CAD
- Engineering
- Tools
- Manufacturing
- Open Source
---
