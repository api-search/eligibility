---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Era Thesis and Era Agency accounts are currently available to US residents only; Era Context connects accounts across the US, the UK, Canada, France, Germany, Spain, and 40+ countries in all.
  entity_types:
  - text: The Services are available only for individuals aged 13 years or older.
    type: individual
  - text: If you are entering into this Agreement on behalf of a company, organization or other legal entity, you represent that you have the authority to bind such entity
    type: business
  minimum_age:
    text: you certify that you are at least 13 years of age
    value: '13'
  restricted_uses:
  - summary: Conduct guidelines
    text: You will not access or use the Services in an unlawful way or for an unlawful or illegitimate purpose.
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
name: Era
provenance_date: '2026-11-09'
provider_name: Era
provider_slug: era
slug: era-eligibility
source_date: '2026-11-09'
source_filename: era-eligibility.yml
source_heading: Eligibility
source_page: https://era.app/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Era\naid: era\nurl: https://era.app/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Era Thesis and Era Agency accounts are currently available to US residents only; Era Context connects accounts\n    across the US, the UK, Canada, France, Germany, Spain, and 40+ countries in all.\nentity_types:\n- type: individual\n  text: The Services are available only for individuals aged 13 years or older.\n- type: business\n  text: If you are entering into this Agreement on behalf of a company, organization or other legal entity, you\n    represent that you have the authority to bind\
  \ such entity\nrestricted_uses:\n- summary: Conduct guidelines\n  text: You will not access or use the Services in an unlawful way or for an unlawful or illegitimate purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you certify that you are at least 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/era/eligibility/era-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Era's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Artificial Intelligence
- Personal Finance
- Wealth Management
- MCP
- Agent-Native
- Open Banking
- OAuth
- Authentication
---
