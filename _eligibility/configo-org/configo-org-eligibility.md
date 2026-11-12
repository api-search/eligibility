---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Services on behalf of a company or other organization, you confirm that you are authorized to bind it, and "you" refers to that organization.
    type: business
  minimum_age:
    text: You must be old enough to consent to the processing of your personal data under the law that applies to you.
    value: null
  restricted_uses:
  - summary: Acceptable Use Policy breaches
    text: use the Services in breach of our Acceptable Use Policy
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
name: Configo
provenance_date: '2026-11-09'
provider_name: Configo
provider_slug: configo-org
slug: configo-org-eligibility
source_date: '2026-11-09'
source_filename: configo-org-eligibility.yml
source_heading: Eligibility
source_page: https://configo.org/docs/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Configo\naid: configo-org\nurl: https://configo.org/docs/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Services on behalf of a company or other organization, you confirm that you are authorized\n    to bind it, and \"you\" refers to that organization.\nrestricted_uses:\n- summary: Acceptable Use Policy breaches\n  text: use the Services in breach of our Acceptable Use Policy\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be\
  \ old enough to consent to the processing of your personal data under the law that applies to\n    you.\n"
source_yaml_url: https://artifacts.apis.io/configo-org/eligibility/configo-org-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Configo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- CPQ
- Product Configurator
- Manufacturing
- Pricing
- CRM
- Inventory Management
- MCP
---
