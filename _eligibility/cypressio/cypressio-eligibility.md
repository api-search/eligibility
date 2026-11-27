---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are at least 18 years of age
    type: individual
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited purposes
    text: you shall not use the Site for any purpose that is unlawful or prohibited by these Terms.
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
name: Cypress.io
provenance_date: '2026-11-09'
provider_name: Cypress.io
provider_slug: cypressio
slug: cypressio-eligibility
source_date: '2026-11-09'
source_filename: cypressio-eligibility.yml
source_heading: Eligibility
source_page: https://www.cypress.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cypress.io\naid: cypressio\nurl: https://www.cypress.io/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are at least 18 years of age\nrestricted_uses:\n- summary: Unlawful or prohibited purposes\n  text: you shall not use the Site for any purpose that is unlawful or prohibited by these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/cypressio/eligibility/cypressio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Cypress.io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Testing
- End-to-End Testing
- Test Automation
- Quality Assurance
- Developer Tools
- CI/CD
- Accessibility
- JavaScript
---
