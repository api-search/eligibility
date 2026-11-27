---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We ship only to U.S. business or residential addresses, not to P.O. boxes, APO, or FPO addresses.
  entity_types:
  - text: you represent that you are at least the age of majority in your state or province of residence
    type: individual
  - text: We reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers, resellers or distributors.
    type: business
  minimum_age:
    text: you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Prohibited uses
    text: (a) for any unlawful purpose;
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
name: Quince
provenance_date: '2026-11-10'
provider_name: Quince
provider_slug: onequince-com
slug: onequince-com-eligibility
source_date: '2026-11-10'
source_filename: onequince-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.quince.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Quince\naid: onequince-com\nurl: https://www.quince.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We ship only to U.S. business or residential addresses, not to P.O. boxes, APO, or FPO addresses.\nentity_types:\n- type: individual\n  text: you represent that you are at least the age of majority in your state or province of residence\n- type: business\n  text: We reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers,\n    resellers or distributors.\nrestricted_uses:\n- summary: Prohibited uses\n  text: (a) for any\
  \ unlawful purpose;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/onequince-com/eligibility/onequince-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Quince's own page on 2026-11-10.
synthetic: false
tags:
- Furniture
- Accessories
- Gifts
- Corporate Gifting
- White Label
---
