---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is available only to individuals who can form legally binding contracts under applicable law.
    type: individual
  - text: When selling through the Shef Marketplace you are operating as a sole proprietor, partnership, limited liability company, limited partnership, corporation or other business entity
    type: business
  minimum_age:
    text: the Service is not available to minors (people under the age of majority in their state or province of residence)
    value: age of majority in state or province of residence
  restricted_uses:
  - summary: Minors excluded
    text: the Service is not available to minors (people under the age of majority in their state or province of residence)
  - summary: Alcohol orders require 21+ recipient
    text: Alcohol cannot be left unattended (contactless delivery is not available for alcohol orders) — someone 21 or older must be present to accept and sign for it.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You agree that we may (but are not required to) obtain information about you, including your criminal records, and you agree to provide any further necessary authorizations to facilitate our access to such records during the term of the Agreement
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Shef
provenance_date: '2026-11-10'
provider_name: Shef
provider_slug: shef
slug: shef-eligibility
source_date: '2026-11-10'
source_filename: shef-eligibility.yml
source_heading: Eligibility
source_page: https://shef.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shef\naid: shef\nurl: https://shef.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Service is available only to individuals who can form legally binding contracts under applicable law.\n- type: business\n  text: When selling through the Shef Marketplace you are operating as a sole proprietor, partnership, limited liability\n    company, limited partnership, corporation or other business entity\nrestricted_uses:\n- summary: Minors excluded\n  text: the Service is not available to minors (people\
  \ under the age of majority in their state or province of residence)\n- summary: Alcohol orders require 21+ recipient\n  text: Alcohol cannot be left unattended (contactless delivery is not available for alcohol orders) — someone 21\n    or older must be present to accept and sign for it.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You agree that we may (but are not required to) obtain information about you, including your criminal records,\n    and you agree to provide any further necessary authorizations to facilitate our access to such records during\n    the term of the Agreement\nminimum_age:\n  value: age of majority in state or province of residence\n  text: the Service is not available to minors (people under the age of majority in their state or province of residence)\n"
source_yaml_url: https://artifacts.apis.io/shef/eligibility/shef-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Shef's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Food Delivery
- Marketplace
- Homemade Food
- Consumer
- Food Tech
- Local Commerce
---
