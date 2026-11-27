---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: No unlawful use
    text: Use the Service for unlawful purposes
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
name: AppLaunchFlow
provenance_date: '2026-11-09'
provider_name: AppLaunchFlow
provider_slug: applaunchflow-com
slug: applaunchflow-com-eligibility
source_date: '2026-11-09'
source_filename: applaunchflow-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.applaunchflow.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AppLaunchFlow\naid: applaunchflow-com\nurl: https://www.applaunchflow.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\nrestricted_uses:\n- summary: No unlawful use\n  text: Use the Service for unlawful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/applaunchflow-com/eligibility/applaunchflow-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AppLaunchFlow's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Marketing
- Artificial Intelligence
- Asset Generation
---
