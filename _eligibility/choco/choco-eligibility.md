---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for use by Users in the United States. You must not use the Service if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United States government.
  entity_types:
  - text: If you open a User Account on behalf of a company, organization, or other entity, then (i) "you" includes you and that entity
    type: business
  - text: In order to use the Service, you must be at least 18 years of age and able to form legally binding contracts under the relevant laws of the jurisdiction where you reside.
    type: individual
  minimum_age:
    text: In order to use the Service, you must be at least 18 years of age and able to form legally binding contracts under the relevant laws of the jurisdiction where you reside.
    value: '18'
  restricted_uses:
  - summary: No commercial solicitation
    text: (viii) using the Service for any commercial solicitation purposes
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
name: Choco
provenance_date: '2026-11-09'
provider_name: Choco
provider_slug: choco
slug: choco-eligibility
source_date: '2026-11-09'
source_filename: choco-eligibility.yml
source_heading: Eligibility
source_page: https://legal.choco.com/us#tandcs
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Choco\naid: choco\nurl: https://legal.choco.com/us#tandcs\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for use by Users in the United States. You must not use the Service if you are a\n    resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by\n    the United States government.\nentity_types:\n- type: business\n  text: If you open a User Account on behalf of a company, organization, or other entity, then (i) \"you\" includes\n    you and that entity\n- type: individual\n  text:\
  \ In order to use the Service, you must be at least 18 years of age and able to form legally binding contracts\n    under the relevant laws of the jurisdiction where you reside.\nrestricted_uses:\n- summary: No commercial solicitation\n  text: (viii) using the Service for any commercial solicitation purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: In order to use the Service, you must be at least 18 years of age and able to form legally binding contracts\n    under the relevant laws of the jurisdiction where you reside.\n"
source_yaml_url: https://artifacts.apis.io/choco/eligibility/choco-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Choco's own page on 2026-11-09.
synthetic: false
tags:
- Restaurant
- Ordering
- Food Distribution
- Suppliers
- ERP Integration
- Artificial Intelligence
- Supply Chain
- Food Service
---
