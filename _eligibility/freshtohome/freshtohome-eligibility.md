---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any person can sign up for services provided if he or she is competent to enter a contract.
    type: individual
  minimum_age:
    text: has attained the age of 18 years
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: To use the platform to transact for lawful purposes in compliance with all applicable laws and regulation.
  - summary: Prohibited platform uses
    text: Disseminating any objectionable material, harassing, libelous, abusive, threatening, harmful, vulgar, obscene, or any unlawful activity.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: authorize FTH to validate the information provided at any point to time and reject registration if any details are found to be untrue wholly or partly.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: FreshToHome
provenance_date: '2026-11-09'
provider_name: FreshToHome
provider_slug: freshtohome
slug: freshtohome-eligibility
source_date: '2026-11-09'
source_filename: freshtohome-eligibility.yml
source_heading: Eligibility
source_page: https://www.freshtohome.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FreshToHome\naid: freshtohome\nurl: https://www.freshtohome.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Any person can sign up for services provided if he or she is competent to enter a contract.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: To use the platform to transact for lawful purposes in compliance with all applicable laws and regulation.\n- summary: Prohibited platform uses\n  text: Disseminating any objectionable material, harassing, libelous, abusive, threatening, harmful, vulgar, obscene,\n \
  \   or any unlawful activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: authorize FTH to validate the information provided at any point to time and reject registration if any details\n    are found to be untrue wholly or partly.\nminimum_age:\n  value: '18'\n  text: has attained the age of 18 years\n"
source_yaml_url: https://artifacts.apis.io/freshtohome/eligibility/freshtohome-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from FreshToHome's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Food and Beverage
- Grocery
- Retail
- Direct to Consumer
- Supply Chain
- Delivery
- India
- United Arab Emirates
---
