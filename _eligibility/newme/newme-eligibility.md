---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Use of Newme.asia is available only to persons who can form a legally binding contract under the Indian Contract Act, 1872.
    type: individual
  minimum_age:
    text: If you are a minor i.e. under the age of 18 years, you may use Newme.asia only with the involvement of a parent or guardian.
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited content and activities
    text: 'The following activities are not permitted on the website/application: for fraudulent purposes, or in connection with a criminal offense or other unlawful activity'
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
name: Newme
provenance_date: '2026-11-10'
provider_name: Newme
provider_slug: newme
slug: newme-eligibility
source_date: '2026-11-10'
source_filename: newme-eligibility.yml
source_heading: Eligibility
source_page: https://newme.asia/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Newme\naid: newme\nurl: https://newme.asia/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Use of Newme.asia is available only to persons who can form a legally binding contract under the Indian\n    Contract Act, 1872.\nrestricted_uses:\n- summary: Unlawful or prohibited content and activities\n  text: 'The following activities are not permitted on the website/application: for fraudulent purposes, or in connection\n    with a criminal offense or other unlawful activity'\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are a minor i.e. under the age of 18 years, you may use Newme.asia only with the involvement of a\n    parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/newme/eligibility/newme-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Newme's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Fashion
- E-Commerce
- Retail
- Apparel
- Direct to Consumer
- Mobile Commerce
---
