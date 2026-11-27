---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: for your own personal purposes
    type: individual
  - text: on behalf of yourself or the entity you represent, and you confirm that you have the authority to do so
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Site.
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
name: Amalgament
provenance_date: '2026-11-09'
provider_name: Amalgament
provider_slug: amalgament-com
slug: amalgament-com-eligibility
source_date: '2026-11-09'
source_filename: amalgament-com-eligibility.yml
source_heading: Eligibility
source_page: https://amalgament.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amalgament\naid: amalgament-com\nurl: https://amalgament.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: for your own personal purposes\n- type: business\n  text: on behalf of yourself or the entity you represent, and you confirm that you have the authority to do so\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/amalgament-com/eligibility/amalgament-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Amalgament's own page on 2026-11-09.
synthetic: false
tags:
- Company
- TechnicalTeam
- Automation
- Small Business
- Artificial Intelligence
---
