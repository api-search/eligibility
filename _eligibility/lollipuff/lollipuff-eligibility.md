---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18 years old or older to create an account. Otherwise, account creation and usage will require the supervision and permission of a guardian or parent.
    type: individual
  - text: If your account is a business entity, you represent the authority to bind that entity to these terms and conditions.
    type: business
  minimum_age:
    text: You must be 18 years old or older to create an account.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful content
    text: 'Content must not: infringe on copyright, trademark, or intellectual property, be sexually explicit or obscene, include offensive language, be offensive to any race, ethnicity, gender, sexuality, or religion, depict or promote drug use.'
  verification:
    approval_required: null
    kyb: false
    kyc: false
    text: Lollipuff does not confirm user’s purported identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lollipuff
provenance_date: '2026-11-09'
provider_name: Lollipuff
provider_slug: lollipuff
slug: lollipuff-eligibility
source_date: '2026-11-09'
source_filename: lollipuff-eligibility.yml
source_heading: Eligibility
source_page: https://www.lollipuff.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lollipuff\naid: lollipuff\nurl: https://www.lollipuff.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 18 years old or older to create an account. Otherwise, account creation and usage will require\n    the supervision and permission of a guardian or parent.\n- type: business\n  text: If your account is a business entity, you represent the authority to bind that entity to these terms and\n    conditions.\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: 'Content must not: infringe on copyright,\
  \ trademark, or intellectual property, be sexually explicit or obscene,\n    include offensive language, be offensive to any race, ethnicity, gender, sexuality, or religion, depict or promote\n    drug use.'\nverification:\n  kyc: false\n  kyb: false\n  approval_required: null\n  text: Lollipuff does not confirm user’s purported identity.\nminimum_age:\n  value: '18'\n  text: You must be 18 years old or older to create an account.\n"
source_yaml_url: https://artifacts.apis.io/lollipuff/eligibility/lollipuff-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Lollipuff's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Authentication
- Luxury Goods
- Designer Fashion
- Resale
- Marketplace
- E-Commerce
- Y Combinator
---
