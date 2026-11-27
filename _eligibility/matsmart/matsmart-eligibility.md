---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - SE
    text: © Matsmart In Scandinavia Sverige
  entity_types:
  - text: Vidare får endast en så kallad slutkund handla hos Matsmart.
    type: individual
  minimum_age:
    text: Barn och ungdomar under 18 år får inte handla på www.matsmart.se .
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: För att du ska kunna genomföra ett köp behöver vi skapa ett användarkonto åt dig.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Matsmart
provenance_date: '2026-11-10'
provider_name: Matsmart
provider_slug: matsmart
slug: matsmart-eligibility
source_date: '2026-11-10'
source_filename: matsmart-eligibility.yml
source_heading: Eligibility
source_page: https://www.matsmart.se/info/allmanna-villkor
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Matsmart\naid: matsmart\nurl: https://www.matsmart.se/info/allmanna-villkor\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - SE\n  excluded: []\n  text: © Matsmart In Scandinavia Sverige\nentity_types:\n- type: individual\n  text: Vidare får endast en så kallad slutkund handla hos Matsmart.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: För att du ska kunna genomföra ett köp behöver vi skapa ett användarkonto åt dig.\nminimum_age:\n  value: '18'\n  text: Barn och ungdomar under 18 år får inte handla på www.matsmart.se .\n"
source_yaml_url: https://artifacts.apis.io/matsmart/eligibility/matsmart-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Matsmart's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- E-Commerce
- Retail
- Grocery
- Food Waste
- Sustainability
- Sweden
---
