---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Arlettie's New York showroom events are currently conducted in New York, and online sales may be made available more broadly, subject to shipping availability, applicable law, sanctions, export control requirements
  entity_types:
  - text: You must be at least 18 years of age to use the Site.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use the Site.
    value: '18'
  restricted_uses:
  - summary: Resale and bulk purchasing
    text: 'Grounds for such action may include, without limitation: suspected or actual resale activity; bulk purchasing'
  - summary: Automated purchasing tools
    text: use of automated purchasing tools
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Arlettie may require Users to register for events and may require presentation of a valid ID upon entry to the showroom.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Arlettie
provenance_date: '2026-11-09'
provider_name: Arlettie
provider_slug: arlettie
slug: arlettie-eligibility
source_date: '2026-11-09'
source_filename: arlettie-eligibility.yml
source_heading: Eligibility
source_page: https://www.arlettie.com/us/en/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arlettie\naid: arlettie\nurl: https://www.arlettie.com/us/en/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Arlettie's New York showroom events are currently conducted in New York, and online sales may be made available\n    more broadly, subject to shipping availability, applicable law, sanctions, export control requirements\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Site.\nrestricted_uses:\n- summary: Resale and bulk purchasing\n  text: 'Grounds for such action may include, without limitation: suspected\
  \ or actual resale activity; bulk purchasing'\n- summary: Automated purchasing tools\n  text: use of automated purchasing tools\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Arlettie may require Users to register for events and may require presentation of a valid ID upon entry\n    to the showroom.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/arlettie/eligibility/arlettie-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Arlettie's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Retail
- E-Commerce
- Fashion
- Luxury
- Private Sales
- Marketplace
- Shopify
- Agentic Commerce
- MCP
- Universal Commerce Protocol
---
