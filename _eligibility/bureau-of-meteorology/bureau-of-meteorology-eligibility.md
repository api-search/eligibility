---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Aviation use limited to aviation industry
    text: The Licensee agrees that they must not supply, share or in any way provide the aeronautical meteorological Data in its original form or in any product developed from or incorporating such Data to any person who is not a member of the aviation industry.
  - summary: Personal use not for third parties
    text: '"Personal" meaning that the Data supplied will be used for personal purposes only and the Licensee may not supply the Data to third parties.'
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
name: Bureau of Meteorology
provenance_date: '2026-11-09'
provider_name: Bureau of Meteorology
provider_slug: bureau-of-meteorology
slug: bureau-of-meteorology-eligibility
source_date: '2026-11-09'
source_filename: bureau-of-meteorology-eligibility.yml
source_heading: Eligibility
source_page: https://www.bom.gov.au/sites/default/files/2026-10/bureau-of-meteorology-data-licence-agreement-october-2026.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bureau of Meteorology\naid: bureau-of-meteorology\nurl: https://www.bom.gov.au/sites/default/files/2026-10/bureau-of-meteorology-data-licence-agreement-october-2026.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Aviation use limited to aviation industry\n  text: The Licensee agrees that they must not supply, share or in any way provide the aeronautical meteorological\n    Data in its original form or in any product developed from or incorporating such Data to any person who is not\n    a member of the aviation industry.\n\
  - summary: Personal use not for third parties\n  text: '\"Personal\" meaning that the Data supplied will be used for personal purposes only and the Licensee may\n    not supply the Data to third parties.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bureau-of-meteorology/eligibility/bureau-of-meteorology-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Bureau of Meteorology's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Government
- Weather
- Climate
- Meteorology
- Water
- Open Data
- Australia
---
