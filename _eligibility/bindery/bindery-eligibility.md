---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: the End User resides in a territory to which Bindery ships (currently the USA and Canada only)
  entity_types:
  - text: YOU ARE AT LEAST THIRTEEN (13) YEARS OF AGE, AND IF YOU ARE BETWEEN 13 AND 18, YOU ARE USING THE SERVICE UNDER THE SUPERVISION OF A PARENT OR GUARDIAN
    type: individual
  minimum_age:
    text: YOU ARE AT LEAST THIRTEEN (13) YEARS OF AGE
    value: '13'
  restricted_uses:
  - summary: No scraping for AI training
    text: including for purposes of training any artificial intelligence or machine learning model
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Bindery Books may accept or reject Tastemakers in its sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bindery
provenance_date: '2026-11-09'
provider_name: Bindery
provider_slug: bindery
slug: bindery-eligibility
source_date: '2026-11-09'
source_filename: bindery-eligibility.yml
source_heading: Eligibility
source_page: https://binderybooks.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bindery\naid: bindery\nurl: https://binderybooks.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: the End User resides in a territory to which Bindery ships (currently the USA and Canada only)\nentity_types:\n- type: individual\n  text: YOU ARE AT LEAST THIRTEEN (13) YEARS OF AGE, AND IF YOU ARE BETWEEN 13 AND 18, YOU ARE USING THE SERVICE\n    UNDER THE SUPERVISION OF A PARENT OR GUARDIAN\nrestricted_uses:\n- summary: No scraping for AI training\n  text: including for purposes of training any artificial intelligence or machine\
  \ learning model\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Bindery Books may accept or reject Tastemakers in its sole discretion.\nminimum_age:\n  value: '13'\n  text: YOU ARE AT LEAST THIRTEEN (13) YEARS OF AGE\n"
source_yaml_url: https://artifacts.apis.io/bindery/eligibility/bindery-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Bindery's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Publishing
- Books
- Community
- Book Clubs
- Media
- Membership
- Consumer
- Marketplace
---
