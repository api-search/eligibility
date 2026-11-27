---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services described on the Site are intended for and are limited to users in the United States, and may be further limited based upon product approvals and other regulatory considerations.
  entity_types:
  - text: you warrant that you are at least 18 years of age or the age of majority in your jurisdiction.
    type: individual
  minimum_age:
    text: you warrant that you are at least 18 years of age or the age of majority in your jurisdiction.
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
name: Jetty
provenance_date: '2026-11-09'
provider_name: Jetty
provider_slug: jetty
slug: jetty-eligibility
source_date: '2026-11-09'
source_filename: jetty-eligibility.yml
source_heading: Eligibility
source_page: https://www.jetty.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jetty\naid: jetty\nurl: https://www.jetty.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services described on the Site are intended for and are limited to users in the United States, and may\n    be further limited based upon product approvals and other regulatory considerations.\nentity_types:\n- type: individual\n  text: you warrant that you are at least 18 years of age or the age of majority in your jurisdiction.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you\
  \ warrant that you are at least 18 years of age or the age of majority in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/jetty/eligibility/jetty-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Jetty's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurtech
- Renters Insurance
- Security Deposit
- Real Estate
- PropTech
- Fintech
- Credit Building
---
