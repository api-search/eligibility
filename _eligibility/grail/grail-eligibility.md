---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information on this site is intended for audiences in the United States only.
  entity_types:
  - text: You must be at least eighteen (18) years of age to access and/or use our Site.
    type: individual
  minimum_age:
    text: You must be at least eighteen (18) years of age to access and/or use our Site.
    value: '18'
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
name: Grail
provenance_date: '2026-11-09'
provider_name: Grail
provider_slug: grail
slug: grail-eligibility
source_date: '2026-11-09'
source_filename: grail-eligibility.yml
source_heading: Eligibility
source_page: https://grail.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Grail\naid: grail\nurl: https://grail.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information on this site is intended for audiences in the United States only.\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years of age to access and/or use our Site.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age to access and/or use our Site.\n"
source_yaml_url: https://artifacts.apis.io/grail/eligibility/grail-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Grail's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Life Sciences
- Healthcare
- Cancer Detection
- Diagnostics
- Genomics
- Multi-Cancer Early Detection
- Bioinformatics
---
