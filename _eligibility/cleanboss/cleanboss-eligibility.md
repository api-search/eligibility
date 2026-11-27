---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Company Sites are not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation.
  entity_types:
  - text: A USER MUST BE AT LEAST AGE 13 TO ACCESS AND USE THE COMPANY SITES.
    type: individual
  - text: These Terms constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: A USER MUST BE AT LEAST AGE 13 TO ACCESS AND USE THE COMPANY SITES.
    value: '13'
  restricted_uses:
  - summary: Use to advertise or sell goods and services
    text: Use the Company Sites to advertise or offer to sell goods and services.
  - summary: Unsolicited advertising or solicitation
    text: Upload, transmit, email, post, or otherwise communicate any advertising or promotional materials
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to participate in certain areas of our Company Sites, you may need to register for an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CleanBoss
provenance_date: '2026-11-09'
provider_name: CleanBoss
provider_slug: cleanboss
slug: cleanboss-eligibility
source_date: '2026-11-09'
source_filename: cleanboss-eligibility.yml
source_heading: Eligibility
source_page: https://www.cleanboss.co/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CleanBoss\naid: cleanboss\nurl: https://www.cleanboss.co/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Company Sites are not intended for distribution to or use by any person or entity in any jurisdiction\n    or country where such distribution or use would be contrary to law or regulation.\nentity_types:\n- type: individual\n  text: A USER MUST BE AT LEAST AGE 13 TO ACCESS AND USE THE COMPANY SITES.\n- type: business\n  text: These Terms constitute a legally binding agreement made between you, whether personally or on behalf of\n    an entity\nrestricted_uses:\n\
  - summary: Use to advertise or sell goods and services\n  text: Use the Company Sites to advertise or offer to sell goods and services.\n- summary: Unsolicited advertising or solicitation\n  text: Upload, transmit, email, post, or otherwise communicate any advertising or promotional materials\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to participate in certain areas of our Company Sites, you may need to register for an account.\nminimum_age:\n  value: '13'\n  text: A USER MUST BE AT LEAST AGE 13 TO ACCESS AND USE THE COMPANY SITES.\n"
source_yaml_url: https://artifacts.apis.io/cleanboss/eligibility/cleanboss-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from CleanBoss's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer Products
- Cleaning
- Eco-friendly
- E-Commerce
---
