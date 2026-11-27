---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is not currently offered to residents of Illinois, Texas, Washington, or Oregon, and may be unavailable in other regions
  entity_types:
  - text: You must be at least 18 years old to contribute.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to contribute.
    value: '18'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: No payout is earned until a submission has received final approval under our review process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Human Archive
provenance_date: '2026-11-09'
provider_name: Human Archive
provider_slug: human-archive
slug: human-archive-eligibility
source_date: '2026-11-09'
source_filename: human-archive-eligibility.yml
source_heading: Eligibility
source_page: https://www.humanarchive.ai/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Human Archive\naid: human-archive\nurl: https://www.humanarchive.ai/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is not currently offered to residents of Illinois, Texas, Washington, or Oregon, and may be\n    unavailable in other regions\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to contribute.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: No payout is earned until a submission has received final approval under our review process.\nminimum_age:\n  value: '18'\n  text:\
  \ You must be at least 18 years old to contribute.\n"
source_yaml_url: https://artifacts.apis.io/human-archive/eligibility/human-archive-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Human Archive's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Artificial Intelligence
- Machine Learning
- Datasets
- Robotics
- Multi-Modal
- Data Labeling
---
