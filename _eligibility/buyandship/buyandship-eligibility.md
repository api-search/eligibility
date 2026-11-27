---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Neither the information provided on any of the Sites nor the provision of any of the Services is intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: All of the Sites are intended for users who are at least 18 years of age.
    type: individual
  minimum_age:
    text: All of the Sites are intended for users who are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Commercial endeavors
    text: These Sites may not be used in connection with any commercial endeavors except those that are specifically endorsed or approved by either of Buy&Ship and B4U.
  - summary: Resale and dealer orders
    text: B4U reserves the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers, resellers or distributors.
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
name: Buyandship
provenance_date: '2026-11-09'
provider_name: Buyandship
provider_slug: buyandship
slug: buyandship-eligibility
source_date: '2026-11-09'
source_filename: buyandship-eligibility.yml
source_heading: Eligibility
source_page: https://www.buyandship.today/en/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Buyandship\naid: buyandship\nurl: https://www.buyandship.today/en/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Neither the information provided on any of the Sites nor the provision of any of the Services is intended\n    for distribution to or use by any person or entity in any jurisdiction or country where such distribution or\n    use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: All of the Sites are intended for users who are at least 18 years of age.\nrestricted_uses:\n- summary: Commercial endeavors\n  text:\
  \ These Sites may not be used in connection with any commercial endeavors except those that are specifically\n    endorsed or approved by either of Buy&Ship and B4U.\n- summary: Resale and dealer orders\n  text: B4U reserves the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers,\n    resellers or distributors.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: All of the Sites are intended for users who are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/buyandship/eligibility/buyandship-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Buyandship's own page on 2026-11-09.
synthetic: false
tags:
- Company
- ParcelForwarding
- GlobalShopping
- Hong Kong
- E-Commerce
---
