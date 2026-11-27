---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual over 18 years of age and of legal age to form a binding contract.
    type: individual
  minimum_age:
    text: You represent and warrant that you are an individual over 18 years of age and of legal age to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: is dangerous, harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise objectionable
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
name: Gel Data
provenance_date: '2026-11-09'
provider_name: Gel Data
provider_slug: gel-data
slug: gel-data-eligibility
source_date: '2026-11-09'
source_filename: gel-data-eligibility.yml
source_heading: Eligibility
source_page: https://www.geldata.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gel Data\naid: gel-data\nurl: https://www.geldata.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual over 18 years of age and of legal age to form a binding\n    contract.\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: is dangerous, harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise\n    objectionable\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: You represent and warrant that you are an individual over 18 years of age and of legal age to form a binding\n    contract.\n"
source_yaml_url: https://artifacts.apis.io/gel-data/eligibility/gel-data-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Gel Data's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Open Source
- Database
- PostgreSQL
- Graph Database
- GraphQL
- Authentication
- Artificial Intelligence
- Vector Search
- Developer Tools
---
