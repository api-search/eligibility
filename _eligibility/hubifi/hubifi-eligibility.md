---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are allowed to legally use these services in the US and other countries and are not barred from doing so by any legal entities.
  entity_types:
  - text: you have the authority to enter into the Terms of Use personally or on behalf of the entity you have named as the user
    type: business
  minimum_age:
    text: You are also certifying that you are (1) over the age of 18
    value: '18'
  restricted_uses:
  - summary: Illegal or fraudulent activities
    text: engage in or assist with, or enable others to engage in, illegal or fraudulent activities
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
name: Hubifi
provenance_date: '2026-11-09'
provider_name: Hubifi
provider_slug: hubifi
slug: hubifi-eligibility
source_date: '2026-11-09'
source_filename: hubifi-eligibility.yml
source_heading: Eligibility
source_page: https://www.hubifi.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hubifi\naid: hubifi\nurl: https://www.hubifi.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are allowed to legally use these services in the US and other countries and are not barred from doing\n    so by any legal entities.\nentity_types:\n- type: business\n  text: you have the authority to enter into the Terms of Use personally or on behalf of the entity you have named\n    as the user\nrestricted_uses:\n- summary: Illegal or fraudulent activities\n  text: engage in or assist with, or enable others to engage in, illegal or fraudulent activities\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are also certifying that you are (1) over the age of 18\n"
source_yaml_url: https://artifacts.apis.io/hubifi/eligibility/hubifi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Hubifi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Revenue Recognition
- Accounting
- Financial Automation
- ASC 606
- Order-to-Cash
- Reconciliation
- Software-as-a-Service
- Fintech
- Integration
---
