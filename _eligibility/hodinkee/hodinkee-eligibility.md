---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using THE Site, you acknowledge that you ARE AT LEAST the age of majority in your jurisdiction
    type: individual
  minimum_age:
    text: The Site(s) is meant for users 18 years old and over.
    value: '18'
  restricted_uses:
  - summary: Commercial use of site content
    text: reproduce, duplicate, copy, sell or otherwise exploit the Site(s) or any image, page layout, page design, trade dress, trademark, logo or other content (“Site Content”) for any commercial purpose
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
name: Hodinkee
provenance_date: '2026-11-09'
provider_name: Hodinkee
provider_slug: hodinkee
slug: hodinkee-eligibility
source_date: '2026-11-09'
source_filename: hodinkee-eligibility.yml
source_heading: Eligibility
source_page: https://www.hodinkee.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hodinkee\naid: hodinkee\nurl: https://www.hodinkee.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using THE Site, you acknowledge that you ARE AT LEAST the age of majority in your jurisdiction\nrestricted_uses:\n- summary: Commercial use of site content\n  text: reproduce, duplicate, copy, sell or otherwise exploit the Site(s) or any image, page layout, page design,\n    trade dress, trademark, logo or other content (“Site Content”) for any commercial purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site(s) is meant for users 18 years old and over.\n"
source_yaml_url: https://artifacts.apis.io/hodinkee/eligibility/hodinkee-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Hodinkee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Watches
- Luxury Goods
- E-Commerce
- Media
- Publishing
- Retail
- Agentic Commerce
- MCP
- Shopify
---
