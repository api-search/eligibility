---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is intended for users who are at least 18 years old.
    type: individual
  - text: whether personally or on behalf of an entity (“you”)
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for the Site
    value: '18'
  restricted_uses:
  - summary: Unauthorized products
    text: 'Among unauthorized Marketplace Offerings are the following: intoxicants of any sort; illegal drugs or other illegal products; alcoholic beverages; games of chance; and pornography or graphic adult content, images, or other adult products.'
  - summary: Industry-regulated use
    text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use this Site.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register with the Site in order to access the Marketplace Offerings.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Foraged
provenance_date: '2026-11-09'
provider_name: Foraged
provider_slug: foraged
slug: foraged-eligibility
source_date: '2026-11-09'
source_filename: foraged-eligibility.yml
source_heading: Eligibility
source_page: https://www.foraged.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Foraged\naid: foraged\nurl: https://www.foraged.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is intended for users who are at least 18 years old.\n- type: business\n  text: whether personally or on behalf of an entity (“you”)\nrestricted_uses:\n- summary: Unauthorized products\n  text: 'Among unauthorized Marketplace Offerings are the following: intoxicants of any sort; illegal drugs or other\n    illegal products; alcoholic beverages; games of chance; and pornography or graphic adult content, images,\
  \ or\n    other adult products.'\n- summary: Industry-regulated use\n  text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and\n    Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use this Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register with the Site in order to access the Marketplace Offerings.\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register for the Site\n"
source_yaml_url: https://artifacts.apis.io/foraged/eligibility/foraged-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Foraged's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Food
- E-Commerce
- Specialty Food
- Consumer
- Wild Food
---
