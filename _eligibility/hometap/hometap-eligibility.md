---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: This website provides information regarding services and products that are made available in certain states in the United States only.
  entity_types:
  - text: Your use of the Site is personal to you and is not transferable by you to any person or entity.
    type: individual
  minimum_age:
    text: you represent that you are (i) at least 18 years or older if the age of majority is greater in your state
    value: '18'
  restricted_uses:
  - summary: Automated data gathering
    text: use any data mining, robots, or similar data gathering and extraction tools in connection with the Site
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Hometap may deny your application at any time for any reason or no reason at all.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hometap
provenance_date: '2026-11-09'
provider_name: Hometap
provider_slug: hometap
slug: hometap-eligibility
source_date: '2026-11-09'
source_filename: hometap-eligibility.yml
source_heading: Eligibility
source_page: https://www.hometap.com/legal?section=terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hometap\naid: hometap\nurl: https://www.hometap.com/legal?section=terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: This website provides information regarding services and products that are made available in certain states\n    in the United States only.\nentity_types:\n- type: individual\n  text: Your use of the Site is personal to you and is not transferable by you to any person or entity.\nrestricted_uses:\n- summary: Automated data gathering\n  text: use any data mining, robots, or similar data gathering and extraction tools in connection with the\
  \ Site\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Hometap may deny your application at any time for any reason or no reason at all.\nminimum_age:\n  value: '18'\n  text: you represent that you are (i) at least 18 years or older if the age of majority is greater in your state\n"
source_yaml_url: https://artifacts.apis.io/hometap/eligibility/hometap-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Hometap's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Home Equity
- Real Estate
- Lending
- Mortgage
- Consumer Finance
- PropTech
---
