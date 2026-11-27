---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents and warrants that it is not located in a jurisdiction subject to a comprehensive U.S. embargo and that it is not listed on any U.S. government restricted party list.
  entity_types:
  - text: You must be at least 18 years old and have the legal capacity to form a binding contract.
    type: individual
  - text: If you are accepting these Terms on behalf of an organization, you represent and warrant that you have authority to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old and have the legal capacity to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Protected health information
    text: Absent a fully executed BAA, Customer agrees not to submit, store, transmit, or otherwise process any PHI through the Services.
  - summary: Sensitive personal data
    text: Customer agrees not to submit protected health information, government identification numbers, payment card numbers, or other categories of highly sensitive personal data to the Services.
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
name: Integuru
provenance_date: '2026-11-09'
provider_name: Integuru
provider_slug: integuru
slug: integuru-eligibility
source_date: '2026-11-09'
source_filename: integuru-eligibility.yml
source_heading: Eligibility
source_page: https://www.integuru.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Integuru\naid: integuru\nurl: https://www.integuru.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents and warrants that it is not located in a jurisdiction subject to a comprehensive U.S.\n    embargo and that it is not listed on any U.S. government restricted party list.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and have the legal capacity to form a binding contract.\n- type: business\n  text: If you are accepting these Terms on behalf of an organization, you represent and warrant that you have authority\n    to bind\
  \ that organization.\nrestricted_uses:\n- summary: Protected health information\n  text: Absent a fully executed BAA, Customer agrees not to submit, store, transmit, or otherwise process any PHI\n    through the Services.\n- summary: Sensitive personal data\n  text: Customer agrees not to submit protected health information, government identification numbers, payment card\n    numbers, or other categories of highly sensitive personal data to the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and have the legal capacity to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/integuru/eligibility/integuru-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Integuru's own page on 2026-11-09.
synthetic: false
tags:
- Company
- API Generation
- Automation
- Integration
- Y Combinator
---
