---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is intended for business professionals and organizations interested in Hyphen's products.
    type: business
  minimum_age:
    text: you must be at least 18 years old to use it.
    value: '18'
  restricted_uses:
  - summary: Violation of law or sanctions
    text: You may not use, export, or re-export Site content or software in violation of U.S. export control or sanctions laws.
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
name: Hyphen
provenance_date: '2026-11-10'
provider_name: Hyphen
provider_slug: usehyphen-com
slug: usehyphen-com-eligibility
source_date: '2026-11-10'
source_filename: usehyphen-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.usehyphen.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hyphen\naid: usehyphen-com\nurl: https://www.usehyphen.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Site is intended for business professionals and organizations interested in Hyphen's products.\nrestricted_uses:\n- summary: Violation of law or sanctions\n  text: You may not use, export, or re-export Site content or software in violation of U.S. export control or sanctions\n    laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must\
  \ be at least 18 years old to use it.\n"
source_yaml_url: https://artifacts.apis.io/usehyphen-com/eligibility/usehyphen-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Hyphen's own page on 2026-11-10.
synthetic: false
tags:
- Food Production
- Kitchen Management
- Order Management
- Inventory Forecasting
- Labor Management
---
