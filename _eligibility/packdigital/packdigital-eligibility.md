---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: refer to the individual, company, or other entity that accepts the Agreement
    type: individual
  - text: If you are a company or other entity, the individual accepting this Agreement on your behalf represents and warrants that they have authority to bind you to this Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited Data
    text: (m) use the Services with Prohibited Data.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access the Services, Customer and its Users must register for an account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Packdigital
provenance_date: '2026-11-10'
provider_name: Packdigital
provider_slug: packdigital
slug: packdigital-eligibility
source_date: '2026-11-10'
source_filename: packdigital-eligibility.yml
source_heading: Eligibility
source_page: https://www.packdigital.com/pages/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Packdigital\naid: packdigital\nurl: https://www.packdigital.com/pages/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: refer to the individual, company, or other entity that accepts the Agreement\n- type: business\n  text: If you are a company or other entity, the individual accepting this Agreement on your behalf represents\n    and warrants that they have authority to bind you to this Agreement.\nrestricted_uses:\n- summary: Prohibited Data\n  text: (m) use the Services with Prohibited Data.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: To access the Services, Customer and its Users must register for an account\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/packdigital/eligibility/packdigital-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Packdigital's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Content Management
- Headless Commerce
- Shopify
- CMS
- A/B Testing
- GraphQL
- MCP
- Agents
- Storefront
- Shopify Hydrogen
---
