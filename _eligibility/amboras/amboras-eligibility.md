---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Export Compliance: You will comply with all applicable export and import control and sanctions laws and represent that you are not located in an embargoed country or on any restricted-party list.'
  entity_types:
  - text: You confirm that you are acquiring the Services for the purpose of carrying on a business activity and not for personal, household, or family purposes.
    type: business
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your jurisdiction, if higher) to use the Services.
    value: '18'
  restricted_uses:
  - summary: Unlawful or infringing sales
    text: use the Services for any unlawful purpose, or to sell goods or services that are unlawful, that infringe third-party rights, or that violate our Acceptable Use Policy
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
name: Amboras
provenance_date: '2026-11-09'
provider_name: Amboras
provider_slug: amboras
slug: amboras-eligibility
source_date: '2026-11-09'
source_filename: amboras-eligibility.yml
source_heading: Eligibility
source_page: https://www.amboras.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amboras\naid: amboras\nurl: https://www.amboras.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Export Compliance: You will comply with all applicable export and import control and sanctions laws and\n    represent that you are not located in an embargoed country or on any restricted-party list.'\nentity_types:\n- type: business\n  text: You confirm that you are acquiring the Services for the purpose of carrying on a business activity and not\n    for personal, household, or family purposes.\nrestricted_uses:\n- summary: Unlawful or infringing sales\n  text: use the Services\
  \ for any unlawful purpose, or to sell goods or services that are unlawful, that infringe\n    third-party rights, or that violate our Acceptable Use Policy\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction, if higher) to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/amboras/eligibility/amboras-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Amboras's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Artificial Intelligence
- Generative AI
- Automation
- Conversion Rate Optimization
- Retail
- No-Code Store Builder
- Y Combinator
- Agentic Commerce
- Storefront
- Payments
- Checkout
- Analytics
- Headless Commerce
- Medusa
- Plugins
- Multi-Tenant
---
