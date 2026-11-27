---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you live in the UK/EEA, the following clause applies.
  entity_types:
  - text: You must be at least 13 years old to use our Products
    type: individual
  - text: If you are using the Products on behalf of a business or some other entity, you represent that you are authorized to bind that business or entity to these Terms
    type: business
  minimum_age:
    text: You must be at least 13 years old to use our Products, or if the age of lawful consent under the laws of your country of residence is older than 13, you must be at least the age of lawful consent to use our Products.
    value: '13'
  restricted_uses:
  - summary: No large-scale collection or commercial use
    text: It does not permit large scale collection or commercial use of any content, data, information, or other materials available in our Products
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: If you open a Clubhouse account, you must provide us with accurate and complete information to allow us to create, verify, and maintain your account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Clubhouse
provenance_date: '2026-11-09'
provider_name: Clubhouse
provider_slug: clubhouse
slug: clubhouse-eligibility
source_date: '2026-11-09'
source_filename: clubhouse-eligibility.yml
source_heading: Eligibility
source_page: https://tos.clubhouse.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clubhouse\naid: clubhouse\nurl: https://tos.clubhouse.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you live in the UK/EEA, the following clause applies.\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use our Products\n- type: business\n  text: If you are using the Products on behalf of a business or some other entity, you represent that you are authorized\n    to bind that business or entity to these Terms\nrestricted_uses:\n- summary: No large-scale collection or commercial use\n  text: It does not permit large scale collection or commercial\
  \ use of any content, data, information, or other\n    materials available in our Products\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: If you open a Clubhouse account, you must provide us with accurate and complete information to allow us\n    to create, verify, and maintain your account.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use our Products, or if the age of lawful consent under the laws of\n    your country of residence is older than 13, you must be at least the age of lawful consent to use our Products.\n"
source_yaml_url: https://artifacts.apis.io/clubhouse/eligibility/clubhouse-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Clubhouse's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Social Audio
- Social Network
- Live Audio
- Voice
- Communications
- Consumer
- Mobile App
---
