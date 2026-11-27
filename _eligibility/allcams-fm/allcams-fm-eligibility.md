---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This site is for people aged 18 or over.
    type: individual
  minimum_age:
    text: This site is for people aged 18 or over.
    value: '18'
  restricted_uses:
  - summary: Unlawful adult content access
    text: use the site where accessing adult content is unlawful in your location
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
name: Allcams
provenance_date: '2026-11-09'
provider_name: Allcams
provider_slug: allcams-fm
slug: allcams-fm-eligibility
source_date: '2026-11-09'
source_filename: allcams-fm-eligibility.yml
source_heading: Eligibility
source_page: https://allcams.fm/en/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Allcams\naid: allcams-fm\nurl: https://allcams.fm/en/legal/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This site is for people aged 18 or over.\nrestricted_uses:\n- summary: Unlawful adult content access\n  text: use the site where accessing adult content is unlawful in your location\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This site is for people aged 18 or over.\n"
source_yaml_url: https://artifacts.apis.io/allcams-fm/eligibility/allcams-fm-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Allcams's own page on 2026-11-09.
synthetic: false
tags:
- Adult
- Cam Aggregator
- Live Streaming
- Entertainment
- Adult Content
---
