---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'International Data Transfers: If you are an EU/EEA/Swiss/UK data subject or a Brazil data subject, you hereby consent to the transfer of your personal data'
  entity_types:
  - text: If you are under 18, you may use our Site and use/purchase our Services only with the involvement and permission of your parent or guardian.
    type: individual
  minimum_age:
    text: If you are under 18, you may use our Site and use/purchase our Services only with the involvement and permission of your parent or guardian.
    value: '18'
  restricted_uses:
  - summary: Non-personal or commercial use
    text: Use our Site or Services (i) for any fraudulent purpose or (ii) for commercial or non-personal purposes;
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
name: Bombas
provenance_date: '2026-11-09'
provider_name: Bombas
provider_slug: bombas
slug: bombas-eligibility
source_date: '2026-11-09'
source_filename: bombas-eligibility.yml
source_heading: Eligibility
source_page: https://shop.bombas.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bombas\naid: bombas\nurl: https://shop.bombas.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'International Data Transfers: If you are an EU/EEA/Swiss/UK data subject or a Brazil data subject, you\n    hereby consent to the transfer of your personal data'\nentity_types:\n- type: individual\n  text: If you are under 18, you may use our Site and use/purchase our Services only with the involvement and permission\n    of your parent or guardian.\nrestricted_uses:\n- summary: Non-personal or commercial use\n  text: Use our Site or Services (i) for any fraudulent\
  \ purpose or (ii) for commercial or non-personal purposes;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18, you may use our Site and use/purchase our Services only with the involvement and permission\n    of your parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/bombas/eligibility/bombas-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Bombas's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Retail
- E-Commerce
- Apparel
- Direct to Consumer
- Commerce
- Agentic Commerce
- Universal Commerce Protocol
- MCP
- Shopify
---
