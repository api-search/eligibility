---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 13 or older to use the Service. By signing in you represent that you meet this age requirement.
    type: individual
  minimum_age:
    text: You must be 13 or older to use the Service.
    value: '13'
  restricted_uses:
  - summary: Resale or sublicensing
    text: Resell or sublicense access to the Service without our written permission.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Sign in via Google or Apple and keep your credentials private.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Card Centering Tool
provenance_date: '2026-11-09'
provider_name: Card Centering Tool
provider_slug: cardcenteringtool-com
slug: cardcenteringtool-com-eligibility
source_date: '2026-11-09'
source_filename: cardcenteringtool-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.cardcenteringtool.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Card Centering Tool\naid: cardcenteringtool-com\nurl: https://www.cardcenteringtool.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 13 or older to use the Service. By signing in you represent that you meet this age requirement.\nrestricted_uses:\n- summary: Resale or sublicensing\n  text: Resell or sublicense access to the Service without our written permission.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Sign in via Google or Apple and keep your credentials private.\nminimum_age:\n\
  \  value: '13'\n  text: You must be 13 or older to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/cardcenteringtool-com/eligibility/cardcenteringtool-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Card Centering Tool's own page on 2026-11-09.
synthetic: false
tags:
- Cards
- Grading
- Trading Cards
- Marketplace
---
