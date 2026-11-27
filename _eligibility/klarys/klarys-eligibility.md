---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Consentio Platform is a communication and sale platform to be used between entities and professionals trading in the same market.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No special categories of personal data
    text: You agree not to provide Consentio any special categories of personal data, such as racial or ethnic origin, political opinions, religious or philosophical beliefs, or trade union membership, genetic data, biometric data or data concerning your health, sex life or sexual orientation.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require an initial data validation in order to create a Company Account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Klarys
provenance_date: '2026-11-09'
provider_name: Klarys
provider_slug: klarys
slug: klarys-eligibility
source_date: '2026-11-09'
source_filename: klarys-eligibility.yml
source_heading: Eligibility
source_page: https://consentio.co/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Klarys\naid: klarys\nurl: https://consentio.co/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Consentio Platform is a communication and sale platform to be used between entities and professionals\n    trading in the same market.\nrestricted_uses:\n- summary: No special categories of personal data\n  text: You agree not to provide Consentio any special categories of personal data, such as racial or ethnic origin,\n    political opinions, religious or philosophical beliefs, or trade union membership, genetic\
  \ data, biometric data\n    or data concerning your health, sex life or sexual orientation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require an initial data validation in order to create a Company Account\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/klarys/eligibility/klarys-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Klarys's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- eProcurement
- Procurement
- Supply Chain
- Food and Beverage
- Seafood
- Fresh Food
- Retail
- EDI
- Invoicing
- France
---
