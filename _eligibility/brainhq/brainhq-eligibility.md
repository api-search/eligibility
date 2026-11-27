---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a country that is subject to a U.S. Government embargo
  entity_types:
  - text: you are (a) at least 18 years old or (b) you are at least 16 years old and have your parent’s or legal guardian’s permission to use the Apps
    type: individual
  minimum_age:
    text: you are at least 16 years old and have your parent’s or legal guardian’s permission to use the Apps
    value: '16'
  restricted_uses:
  - summary: Prohibited content
    text: You agree that you will not post, exchange, make available, provide, or process any Prohibited Content on the Apps.
  - summary: Export restrictions
    text: No software, technology or other information from our Apps may be downloaded or otherwise exported or re-exported to any person or entity on the U.S. Treasury Department’s list of Specially Designated Nationals
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
name: BrainHQ
provenance_date: '2026-11-09'
provider_name: BrainHQ
provider_slug: brainhq
slug: brainhq-eligibility
source_date: '2026-11-09'
source_filename: brainhq-eligibility.yml
source_heading: Eligibility
source_page: https://www.brainhq.com/en-us/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BrainHQ\naid: brainhq\nurl: https://www.brainhq.com/en-us/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a country that is subject to a U.S. Government embargo\nentity_types:\n- type: individual\n  text: you are (a) at least 18 years old or (b) you are at least 16 years old and have your parent’s or legal guardian’s\n    permission to use the Apps\nrestricted_uses:\n- summary: Prohibited content\n  text: You agree that you will not post, exchange, make available, provide, or process any Prohibited Content on\n    the Apps.\n- summary: Export restrictions\n\
  \  text: No software, technology or other information from our Apps may be downloaded or otherwise exported or re-exported\n    to any person or entity on the U.S. Treasury Department’s list of Specially Designated Nationals\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: you are at least 16 years old and have your parent’s or legal guardian’s permission to use the Apps\n"
source_yaml_url: https://artifacts.apis.io/brainhq/eligibility/brainhq-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from BrainHQ's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Brain Training
- Cognitive Health
- Software-as-a-Service
- Posit-Science
---
