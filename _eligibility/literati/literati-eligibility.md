---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: currently only the United States and U.S. territories
  entity_types:
  - text: The Services are available only to, and may only be used by, individuals who are 18 years and older who can form legally binding contracts under applicable law.
    type: individual
  minimum_age:
    text: The Services are available only to, and may only be used by, individuals who are 18 years and older who can form legally binding contracts under applicable law.
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
name: Literati
provenance_date: '2026-11-09'
provider_name: Literati
provider_slug: literati
slug: literati-eligibility
source_date: '2026-11-09'
source_filename: literati-eligibility.yml
source_heading: Eligibility
source_page: https://literati.com/p/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Literati\naid: literati\nurl: https://literati.com/p/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: currently only the United States and U.S. territories\nentity_types:\n- type: individual\n  text: The Services are available only to, and may only be used by, individuals who are 18 years and older who\n    can form legally binding contracts under applicable law.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are available only to, and may only be used\
  \ by, individuals who are 18 years and older who\n    can form legally binding contracts under applicable law.\n"
source_yaml_url: https://artifacts.apis.io/literati/eligibility/literati-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Literati's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Books
- Publishing
- Education
- Children
- Subscription Commerce
- E-Commerce
- Fundraising
- Schools
- Reading
---
