---
api_specs:
- filename: liquid-death-discovery-api-openapi.yml
  format: yaml
  label: Liquid Death Discovery API
  slug: liquid-death-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liquid-death/openapi/liquid-death-discovery-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - AF
    - CU
    - IR
    - IQ
    - LY
    - KP
    - SY
    served: []
    text: Export controls prohibit download or export into Afghanistan, Cuba, Iran, Iraq, Libya, North Korea, Syria or any other country to which the United States has embargoed goods. Products can be ordered and delivered to certain countries.
  entity_types:
  - text: You must be at least 18 years of age to purchase Products on the Site.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to purchase Products on the Site.
    value: '18'
  restricted_uses:
  - summary: No commercial use of content
    text: 'This license does not include any right to: (a) resell or make any commercial use of the Services or Proprietary Material'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- AF
- CU
- IR
- IQ
- LY
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Liquid Death
provenance_date: '2026-11-09'
provider_name: Liquid Death
provider_slug: liquid-death
slug: liquid-death-eligibility
source_date: '2026-11-09'
source_filename: liquid-death-eligibility.yml
source_heading: Eligibility
source_page: https://liquiddeath.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Liquid Death\naid: liquid-death\nurl: https://liquiddeath.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - AF\n  - CU\n  - IR\n  - IQ\n  - LY\n  - KP\n  - SY\n  text: Export controls prohibit download or export into Afghanistan, Cuba, Iran, Iraq, Libya, North Korea, Syria\n    or any other country to which the United States has embargoed goods. Products can be ordered and delivered to\n    certain countries.\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to purchase Products on the Site.\nrestricted_uses:\n\
  - summary: No commercial use of content\n  text: 'This license does not include any right to: (a) resell or make any commercial use of the Services or Proprietary\n    Material'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to purchase Products on the Site.\n"
source_yaml_url: https://artifacts.apis.io/liquid-death/eligibility/liquid-death-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Liquid Death's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Beverages
- Consumer Packaged Goods
- Direct to Consumer
- E-Commerce
- Retail
- Agentic Commerce
- Universal Commerce Protocol
- MCP
- Shopify
---
