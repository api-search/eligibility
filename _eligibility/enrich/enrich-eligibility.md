---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Enrich makes no claim that the Application is appropriate or may be downloaded outside the United States.
  entity_types:
  - text: The Services are intended solely for persons who are 18 or older.
    type: individual
  minimum_age:
    text: The Services are intended solely for persons who are 18 or older.
    value: '18'
  restricted_uses:
  - summary: Commercial use limited to express permission
    text: You will not use the Service for any commercial or other purposes that are not expressly permitted by these Terms.
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
name: enrich
provenance_date: '2026-11-09'
provider_name: enrich
provider_slug: enrich
slug: enrich-eligibility
source_date: '2026-11-09'
source_filename: enrich-eligibility.yml
source_heading: Eligibility
source_page: https://www.joinenrich.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: enrich\naid: enrich\nurl: https://www.joinenrich.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Enrich makes no claim that the Application is appropriate or may be downloaded outside the United States.\nentity_types:\n- type: individual\n  text: The Services are intended solely for persons who are 18 or older.\nrestricted_uses:\n- summary: Commercial use limited to express permission\n  text: You will not use the Service for any commercial or other purposes that are not expressly permitted by these\n    Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended solely for persons who are 18 or older.\n"
source_yaml_url: https://artifacts.apis.io/enrich/eligibility/enrich-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from enrich's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Membership Network
- Executive Community
- Professional Development
- Networking
- Technology Leaders
---
