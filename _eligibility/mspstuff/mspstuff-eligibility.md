---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Export and sanctions: You will not use the Service in violation of U.S. export control or sanctions laws, or from a sanctioned country.'
  entity_types:
  - text: You must be a business, and each Member must be at least 18 years old.
    type: business
  minimum_age:
    text: each Member must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No regulated health or payment/ID data
    text: The Customer must not use it to deliberately collect or store, payment card numbers, government identification numbers, or health information that is regulated under health-privacy laws such as the U.S. Health Insurance Portability and Accountability Act
  - summary: Not for consumer use
    text: It is not for personal, household or consumer use.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Signup is by invitation. We may accept or decline any application.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AutomatedMSP,
provenance_date: '2026-11-10'
provider_name: AutomatedMSP,
provider_slug: mspstuff
slug: mspstuff-eligibility
source_date: '2026-11-10'
source_filename: mspstuff-eligibility.yml
source_heading: Eligibility
source_page: https://www.mspstuff.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 'AutomatedMSP, '\naid: mspstuff\nurl: https://www.mspstuff.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Export and sanctions: You will not use the Service in violation of U.S. export control or sanctions laws,\n    or from a sanctioned country.'\nentity_types:\n- type: business\n  text: You must be a business, and each Member must be at least 18 years old.\nrestricted_uses:\n- summary: No regulated health or payment/ID data\n  text: The Customer must not use it to deliberately collect or store, payment card numbers, government identification\n    numbers, or health information\
  \ that is regulated under health-privacy laws such as the U.S. Health Insurance\n    Portability and Accountability Act\n- summary: Not for consumer use\n  text: It is not for personal, household or consumer use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Signup is by invitation. We may accept or decline any application.\nminimum_age:\n  value: '18'\n  text: each Member must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/mspstuff/eligibility/mspstuff-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from AutomatedMSP,'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- MSP
- Artificial Intelligence
- Automation
- Software-as-a-Service
---
