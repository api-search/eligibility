---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: WeprovidethisWebsiteforuseonlybypersonslocatedintheUnitedStates.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or commercial use
    text: YoumayusetheWebsiteonlyforlawfulpurposesandinaccordancewiththeseTermsofUse.
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
name: Farmwise
provenance_date: '2026-11-09'
provider_name: Farmwise
provider_slug: farmwise
slug: farmwise-eligibility
source_date: '2026-11-09'
source_filename: farmwise-eligibility.yml
source_heading: Eligibility
source_page: https://farmwise.io/assets/downloads/FarmwiseTOS_20240315.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Farmwise\naid: farmwise\nurl: https://farmwise.io/assets/downloads/FarmwiseTOS_20240315.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: WeprovidethisWebsiteforuseonlybypersonslocatedintheUnitedStates.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or commercial use\n  text: YoumayusetheWebsiteonlyforlawfulpurposesandinaccordancewiththeseTermsofUse.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/farmwise/eligibility/farmwise-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Farmwise's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Agriculture
- AgTech
- Robotics
- Artificial Intelligence
- Computer Vision
- Automation
---
