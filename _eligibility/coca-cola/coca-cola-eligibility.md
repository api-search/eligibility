---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use our Services, you must be at least the age of legal majority in your place of residence and otherwise legally able to enter into a binding contract with Coca-Cola.
    type: individual
  minimum_age:
    text: we do not market directly to children under the age of 13 (or the minimum age required by the laws in your country).
    value: age of legal majority in place of residence
  restricted_uses:
  - summary: Sanctioned jurisdictions and parties
    text: 'You hereby represent and warrant that: (i) you are not located in a country that is subject to a U.S. Government embargo or that has been designated by the U.S. Government as a “terrorist supporting” country; and (ii) you are not listed on any U.S. Government list of prohibited or restricted parties.'
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
name: The Coca-Cola Company
provenance_date: '2026-11-09'
provider_name: The Coca-Cola Company
provider_slug: coca-cola
slug: coca-cola-eligibility
source_date: '2026-11-09'
source_filename: coca-cola-eligibility.yml
source_heading: Eligibility
source_page: https://www.coca-cola.com/us/en/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: The Coca-Cola Company\naid: coca-cola\nurl: https://www.coca-cola.com/us/en/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To use our Services, you must be at least the age of legal majority in your place of residence and otherwise\n    legally able to enter into a binding contract with Coca-Cola.\nrestricted_uses:\n- summary: Sanctioned jurisdictions and parties\n  text: 'You hereby represent and warrant that: (i) you are not located in a country that is subject to a U.S. Government\n   \
  \ embargo or that has been designated by the U.S. Government as a “terrorist supporting” country; and (ii) you\n    are not listed on any U.S. Government list of prohibited or restricted parties.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of legal majority in place of residence\n  text: we do not market directly to children under the age of 13 (or the minimum age required by the laws in your\n    country).\n"
source_yaml_url: https://artifacts.apis.io/coca-cola/eligibility/coca-cola-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from The Coca-Cola Company's own page on 2026-11-09.
synthetic: false
tags:
- Beverages
- Beverage Manufacturer
- Consumer Goods
- Distribution
- Retail
- Supply Chain
- Food and Beverage
- Consumer Packaged Goods
---
