---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and able to enter a binding agreement.
    type: individual
  minimum_age:
    text: You must be at least 18 and able to enter a binding agreement.
    value: '18'
  restricted_uses:
  - summary: HIPAA business-associate work
    text: General hosted services are not offered for HIPAA-regulated business-associate work without a separately reviewed deployment and any required written agreement.
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
name: blacklabelbots-com
provenance_date: '2026-11-09'
provider_name: blacklabelbots-com
provider_slug: blacklabelbots-com
slug: blacklabelbots-com-eligibility
source_date: '2026-11-09'
source_filename: blacklabelbots-com-eligibility.yml
source_heading: Eligibility
source_page: https://blacklabelbots.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: blacklabelbots-com\naid: blacklabelbots-com\nurl: https://blacklabelbots.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and able to enter a binding agreement.\nrestricted_uses:\n- summary: HIPAA business-associate work\n  text: General hosted services are not offered for HIPAA-regulated business-associate work without a separately\n    reviewed deployment and any required written agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: You must be at least 18 and able to enter a binding agreement.\n"
source_yaml_url: https://artifacts.apis.io/blacklabelbots-com/eligibility/blacklabelbots-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from blacklabelbots-com's own page on 2026-11-09.
synthetic: false
tags:
- Business
- Software
- Productivity
- Automation
- Mac
- Windows
---
