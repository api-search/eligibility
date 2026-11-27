---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You agree not to attempt to log on to the Site from any country under sanctions by the Office of Foreign Asset Control (“OFAC”).
  entity_types:
  - text: The Site, and the products and services described on the Site, are intended for use by individuals who are at least 18 years old.
    type: individual
  minimum_age:
    text: The Site, and the products and services described on the Site, are intended for use by individuals who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Commercial use prohibited
    text: You agree that you will not duplicate, reproduce, sell, resell, use or exploit the Content or the Site for any commercial purpose.
  - summary: No automated access
    text: You agree that you will not use any robot, spider, automatic, or manual device to monitor or copy the Site or any Content.
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
name: Kafene
provenance_date: '2026-11-09'
provider_name: Kafene
provider_slug: kafene
slug: kafene-eligibility
source_date: '2026-11-09'
source_filename: kafene-eligibility.yml
source_heading: Eligibility
source_page: https://www.kafene.com/legal/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kafene\naid: kafene\nurl: https://www.kafene.com/legal/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You agree not to attempt to log on to the Site from any country under sanctions by the Office of Foreign\n    Asset Control (“OFAC”).\nentity_types:\n- type: individual\n  text: The Site, and the products and services described on the Site, are intended for use by individuals who are\n    at least 18 years old.\nrestricted_uses:\n- summary: Commercial use prohibited\n  text: You agree that you will not duplicate, reproduce, sell, resell, use or exploit the Content\
  \ or the Site for\n    any commercial purpose.\n- summary: No automated access\n  text: You agree that you will not use any robot, spider, automatic, or manual device to monitor or copy the Site\n    or any Content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site, and the products and services described on the Site, are intended for use by individuals who are\n    at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/kafene/eligibility/kafene-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Kafene's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Lease-to-Own
- Point-of-Sale
- Consumer Finance
- Retail
- Underwriting
- Payments
---
