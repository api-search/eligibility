---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Country refers to Spain
  entity_types:
  - text: the individual accessing or using the Services
    type: individual
  - text: individuals and companies (“Client” or “You”), either conducting business activities on their own or acting as consumers.
    type: business
  minimum_age:
    text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Services.
    value: '18'
  restricted_uses:
  - summary: Sensitive data processing needs approval
    text: Process data considered as ‘sensitive’ under European data protection laws as well as those relating to payment details can only be done as long as you have obtained our prior written approval.
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
name: Vidjet
provenance_date: '2026-11-10'
provider_name: Vidjet
provider_slug: vidjet
slug: vidjet-eligibility
source_date: '2026-11-10'
source_filename: vidjet-eligibility.yml
source_heading: Eligibility
source_page: https://www.vidjet.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vidjet\naid: vidjet\nurl: https://www.vidjet.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Country refers to Spain\nentity_types:\n- type: individual\n  text: the individual accessing or using the Services\n- type: business\n  text: individuals and companies (“Client” or “You”), either conducting business activities on their own or acting\n    as consumers.\nrestricted_uses:\n- summary: Sensitive data processing needs approval\n  text: Process data considered as ‘sensitive’ under European data protection laws as well as those relating to\n    payment details\
  \ can only be done as long as you have obtained our prior written approval.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/vidjet/eligibility/vidjet-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Vidjet's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Video
- Shoppable Video
- Shopify
- Conversion
- Marketing
- No-Code
- Widgets
- Embed
---
