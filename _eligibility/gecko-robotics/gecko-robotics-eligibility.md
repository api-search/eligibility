---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if User is an individual (i.e., not a corporation), User is at least 18 years of age.
    type: individual
  minimum_age:
    text: if User is an individual (i.e., not a corporation), User is at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Unlawful purposes
    text: Users are prohibited from using the Site for any unlawful purposes or activities that could harm Gecko or its affiliates
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
name: Gecko Robotics
provenance_date: '2026-11-09'
provider_name: Gecko Robotics
provider_slug: gecko-robotics
slug: gecko-robotics-eligibility
source_date: '2026-11-09'
source_filename: gecko-robotics-eligibility.yml
source_heading: Eligibility
source_page: https://www.geckorobotics.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gecko Robotics\naid: gecko-robotics\nurl: https://www.geckorobotics.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: if User is an individual (i.e., not a corporation), User is at least 18 years of age.\nrestricted_uses:\n- summary: Unlawful purposes\n  text: Users are prohibited from using the Site for any unlawful purposes or activities that could harm Gecko or\n    its affiliates\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: if User is an individual\
  \ (i.e., not a corporation), User is at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/gecko-robotics/eligibility/gecko-robotics-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Gecko Robotics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Robotics
- Artificial Intelligence
- Industrial
- Asset Management
- Infrastructure
- Inspection
- Defense
- Energy
- Manufacturing
- Predictive Maintenance
---
