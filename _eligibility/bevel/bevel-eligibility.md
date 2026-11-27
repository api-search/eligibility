---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Users must not be located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a "terrorist supporting" country.
  entity_types:
  - text: If an individual, are at least 13 years of age.
    type: individual
  minimum_age:
    text: If an individual, are at least 13 years of age.
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
name: Bevel
provenance_date: '2026-11-09'
provider_name: Bevel
provider_slug: bevel
slug: bevel-eligibility
source_date: '2026-11-09'
source_filename: bevel-eligibility.yml
source_heading: Eligibility
source_page: https://www.bevel.health/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bevel\naid: bevel\nurl: https://www.bevel.health/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Users must not be located in a country that is subject to a U.S. Government embargo, or that has been designated\n    by the U.S. Government as a \"terrorist supporting\" country.\nentity_types:\n- type: individual\n  text: If an individual, are at least 13 years of age.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If an individual, are at least 13 years\
  \ of age.\n"
source_yaml_url: https://artifacts.apis.io/bevel/eligibility/bevel-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Bevel's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health
- Wellness
- Wearables
- Health Data
- Fitness
- Artificial Intelligence
- Consumer Health
---
