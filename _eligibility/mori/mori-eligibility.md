---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    - US
    text: MORI purchases can only be delivered free of charge to addresses within the United Kingdom, including Northern Ireland (excluding PO Box addresses and BFPO addresses), the European Union and the United States of America.
  entity_types:
  - text: In order to register an account you must be an individual and agree to comply with the Terms.
    type: individual
  minimum_age:
    text: If you are under eighteen (18) years of age, you cannot place an order for any products through the Website.
    value: '18'
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: Use of the Website is restricted to personal and non-commercial use only.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may refuse at our absolute discretion any application to join us or receive our services for any reason whatsoever.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MORI
provenance_date: '2026-11-10'
provider_name: MORI
provider_slug: mori
slug: mori-eligibility
source_date: '2026-11-10'
source_filename: mori-eligibility.yml
source_heading: Eligibility
source_page: https://babymori.com/pages/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MORI\naid: mori\nurl: https://babymori.com/pages/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  - US\n  excluded: []\n  text: MORI purchases can only be delivered free of charge to addresses within the United Kingdom, including Northern\n    Ireland (excluding PO Box addresses and BFPO addresses), the European Union and the United States of America.\nentity_types:\n- type: individual\n  text: In order to register an account you must be an individual and agree to comply with the Terms.\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: Use of the Website is\
  \ restricted to personal and non-commercial use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may refuse at our absolute discretion any application to join us or receive our services for any reason\n    whatsoever.\nminimum_age:\n  value: '18'\n  text: If you are under eighteen (18) years of age, you cannot place an order for any products through the Website.\n"
source_yaml_url: https://artifacts.apis.io/mori/eligibility/mori-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from MORI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Retail
- E-Commerce
- Baby Products
- Consumer Goods
- Apparel
- Direct to Consumer
- Shopify
- MCP
- Agent-Native
- Universal Commerce Protocol
---
