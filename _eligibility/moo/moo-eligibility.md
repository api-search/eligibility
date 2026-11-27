---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: These MOO Terms apply if you are using the United States and Canadian versions of the Site.
  entity_types:
  - text: you are a business, and MOO is a service provider as relates to Customer Personal Data
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or prohibited Customer Assets
    text: 'Customer Assets must not: (a) be defamatory of any person; (b) be obscene, offensive, hateful or inflammatory'
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
name: MOO
provenance_date: '2026-11-10'
provider_name: MOO
provider_slug: moo
slug: moo-eligibility
source_date: '2026-11-10'
source_filename: moo-eligibility.yml
source_heading: Eligibility
source_page: https://www.moo.com/us/about/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MOO\naid: moo\nurl: https://www.moo.com/us/about/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: These MOO Terms apply if you are using the United States and Canadian versions of the Site.\nentity_types:\n- type: business\n  text: you are a business, and MOO is a service provider as relates to Customer Personal Data\nrestricted_uses:\n- summary: Unlawful or prohibited Customer Assets\n  text: 'Customer Assets must not: (a) be defamatory of any person; (b) be obscene, offensive, hateful or inflammatory'\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/moo/eligibility/moo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from MOO's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Retail
- Printing
- Print on Demand
- Business Cards
- Design
- Stationery
- Promotional Products
- E-Commerce
---
