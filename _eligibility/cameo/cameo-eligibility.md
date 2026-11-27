---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use our Site
    type: individual
  - text: you have all rights necessary (including from the Business) to request a Business CAMEO Video on behalf of the Business
    type: business
  minimum_age:
    text: You must be at least 13 years old to use our Site, or the applicable legal age to enter into a contract and lawfully use our Site and Services, whichever is greater. In South Carolina, you must be at least 18 years old to use our Site.
    value: '13'
  restricted_uses:
  - summary: No political campaign solicitation
    text: You will not use the Site or any Cameo product or service to promote or solicit contributions on behalf of your candidacy for public office
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
name: Cameo
provenance_date: '2026-11-09'
provider_name: Cameo
provider_slug: cameo
slug: cameo-eligibility
source_date: '2026-11-09'
source_filename: cameo-eligibility.yml
source_heading: Eligibility
source_page: https://legal.cameo.com/termsofservice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cameo\naid: cameo\nurl: https://legal.cameo.com/termsofservice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use our Site\n- type: business\n  text: you have all rights necessary (including from the Business) to request a Business CAMEO Video on behalf\n    of the Business\nrestricted_uses:\n- summary: No political campaign solicitation\n  text: You will not use the Site or any Cameo product or service to promote or solicit contributions on behalf\n    of your candidacy for\
  \ public office\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use our Site, or the applicable legal age to enter into a contract\n    and lawfully use our Site and Services, whichever is greater. In South Carolina, you must be at least 18 years\n    old to use our Site.\n"
source_yaml_url: https://artifacts.apis.io/cameo/eligibility/cameo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cameo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Video
- Marketplace
- Celebrity
- Entertainment
- Personalized Video
- Creator Economy
---
