---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - AE
    text: To be eligible to use the Services, you must be at least 18 years old and a legal resident of the United Arab Emirates.
  entity_types:
  - text: To be eligible to use the Services, you must be at least 18 years old and a legal resident of the United Arab Emirates.
    type: individual
  minimum_age:
    text: To be eligible to use the Services, you must be at least 18 years old and a legal resident of the United Arab Emirates.
    value: '18'
  restricted_uses:
  - summary: Prohibited purchase categories
    text: 'You will not use the Services to purchase: a. Illegal items or conduct any illegal activities or transactions.'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We may also ask you for identifying documents to help us validate your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Go Rise
provenance_date: '2026-11-09'
provider_name: Go Rise
provider_slug: go-rise
slug: go-rise-eligibility
source_date: '2026-11-09'
source_filename: go-rise-eligibility.yml
source_heading: Eligibility
source_page: https://www.gorise.co/rise_terms_condition.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Go Rise\naid: go-rise\nurl: https://www.gorise.co/rise_terms_condition.php\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AE\n  excluded: []\n  text: To be eligible to use the Services, you must be at least 18 years old and a legal resident of the United\n    Arab Emirates.\nentity_types:\n- type: individual\n  text: To be eligible to use the Services, you must be at least 18 years old and a legal resident of the United\n    Arab Emirates.\nrestricted_uses:\n- summary: Prohibited purchase categories\n  text: 'You will not use the Services to purchase: a. Illegal items or conduct any illegal activities\
  \ or transactions.'\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: We may also ask you for identifying documents to help us validate your identity.\nminimum_age:\n  value: '18'\n  text: To be eligible to use the Services, you must be at least 18 years old and a legal resident of the United\n    Arab Emirates.\n"
source_yaml_url: https://artifacts.apis.io/go-rise/eligibility/go-rise-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Go Rise's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Banking
- Financial Services
- Remittances
- Migrant
- Insurance
- Mobile
---
