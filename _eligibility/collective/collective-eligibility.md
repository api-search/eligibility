---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: COLLECTIVE PROVIDES BUSINESS SERVICES FOR BUSINESS ENTITIES
    type: business
  - text: FOR INDIVIDUALS WHO ALSO USE OUR SERVICES FOR THEIR BUSINESS ACTIVITIES.
    type: individual
  minimum_age:
    text: BY USING OR REGISTERING FOR THE WEBSITE AND/OR SERVICES YOU ARE AT LEAST 18 YEARS OF AGE
    value: '18'
  restricted_uses:
  - summary: Illegal income returns
    text: Returns involving illegal income, including income that is legal at the state level, but not legal federally
  - summary: Foreign residents or foreign revenue tax situations
    text: Residents of a foreign country or if you receive revenue from a foreign country
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
name: Collective
provenance_date: '2026-11-09'
provider_name: Collective
provider_slug: collective
slug: collective-eligibility
source_date: '2026-11-09'
source_filename: collective-eligibility.yml
source_heading: Eligibility
source_page: https://www.collective.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Collective\naid: collective\nurl: https://www.collective.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: COLLECTIVE PROVIDES BUSINESS SERVICES FOR BUSINESS ENTITIES\n- type: individual\n  text: FOR INDIVIDUALS WHO ALSO USE OUR SERVICES FOR THEIR BUSINESS ACTIVITIES.\nrestricted_uses:\n- summary: Illegal income returns\n  text: Returns involving illegal income, including income that is legal at the state level, but not legal federally\n- summary: Foreign residents or foreign revenue tax situations\n\
  \  text: Residents of a foreign country or if you receive revenue from a foreign country\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: BY USING OR REGISTERING FOR THE WEBSITE AND/OR SERVICES YOU ARE AT LEAST 18 YEARS OF AGE\n"
source_yaml_url: https://artifacts.apis.io/collective/eligibility/collective-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Collective's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Accounting
- Tax
- Payroll
- Bookkeeping
- Self-Employed
- Financial Services
- Small Business
---
