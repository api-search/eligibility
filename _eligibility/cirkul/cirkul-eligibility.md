---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: in the United States and Canada
  entity_types:
  - text: You represent and warrant that you are at least 18 years of age.
    type: individual
  minimum_age:
    text: You represent and warrant that you are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: All orders of our products must be for personal use only.
  - summary: Services for your own use only
    text: the Services are offered only for your use, and not for the use or benefit of any third party.
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
name: Cirkul
provenance_date: '2026-11-09'
provider_name: Cirkul
provider_slug: cirkul
slug: cirkul-eligibility
source_date: '2026-11-09'
source_filename: cirkul-eligibility.yml
source_heading: Eligibility
source_page: https://drinkcirkul.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cirkul\naid: cirkul\nurl: https://drinkcirkul.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: in the United States and Canada\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least 18 years of age.\nrestricted_uses:\n- summary: Personal use only\n  text: All orders of our products must be for personal use only.\n- summary: Services for your own use only\n  text: the Services are offered only for your use, and not for the use or benefit of any third party.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/cirkul/eligibility/cirkul-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Cirkul's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Beverages
- Consumer Packaged Goods
- Direct to Consumer
- E-Commerce
- Retail
- Subscription Commerce
- Agentic Commerce
- MCP
- Universal Commerce Protocol
- Shopify
- Hydration
---
