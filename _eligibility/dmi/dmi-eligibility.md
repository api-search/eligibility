---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no representation that the Site is appropriate or available for use outside of the United States. Access to the Site from countries or territories or by individuals where such access is illegal is prohibited.
  entity_types:
  - text: You must be at least 18 years old to use the Site.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Site.
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
name: DMI
provenance_date: '2026-11-09'
provider_name: DMI
provider_slug: dmi
slug: dmi-eligibility
source_date: '2026-11-09'
source_filename: dmi-eligibility.yml
source_heading: Eligibility
source_page: https://dminc.com/policies/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DMI\naid: dmi\nurl: https://dminc.com/policies/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no representation that the Site is appropriate or available for use outside of the United States.\n    Access to the Site from countries or territories or by individuals where such access is illegal is prohibited.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Site.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years\
  \ old to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/dmi/eligibility/dmi-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from DMI's own page on 2026-11-09.
synthetic: false
tags:
- Digital Transformation
- Artificial Intelligence
- Cloud Services
- Cybersecurity
- Data Analytics
---
