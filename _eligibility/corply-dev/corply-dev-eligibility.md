---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled from the United States and primarily intended for users forming or operating U.S.-connected companies. You may not use the Services if you are located in, organized under the laws of, or ordinarily resident in a country or region subject to comprehensive U.S. sanctions.
  entity_types:
  - text: You must be at least 18 years old and legally able to enter into a contract.
    type: individual
  - text: If you use the Services for a company, proposed company, organization, or other entity, you represent that you are authorized to bind that entity
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally able to enter into a contract.
    value: '18'
  restricted_uses:
  - summary: No securities, investment, loan or regulated offerings
    text: Do not use the Services to offer, sell, solicit, broker, or recommend securities, investments, loans, banking products, insurance, immigration benefits, or regulated services unless you are fully responsible for compliance and have any required approvals.
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
name: Corply
provenance_date: '2026-11-09'
provider_name: Corply
provider_slug: corply-dev
slug: corply-dev-eligibility
source_date: '2026-11-09'
source_filename: corply-dev-eligibility.yml
source_heading: Eligibility
source_page: https://corply.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Corply\naid: corply-dev\nurl: https://corply.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled from the United States and primarily intended for users forming or operating\n    U.S.-connected companies. You may not use the Services if you are located in, organized under the laws of, or\n    ordinarily resident in a country or region subject to comprehensive U.S. sanctions.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally able to enter into a contract.\n- type: business\n  text: If you use the Services for\
  \ a company, proposed company, organization, or other entity, you represent that\n    you are authorized to bind that entity\nrestricted_uses:\n- summary: No securities, investment, loan or regulated offerings\n  text: Do not use the Services to offer, sell, solicit, broker, or recommend securities, investments, loans, banking\n    products, insurance, immigration benefits, or regulated services unless you are fully responsible for compliance\n    and have any required approvals.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter into a contract.\n"
source_yaml_url: https://artifacts.apis.io/corply-dev/eligibility/corply-dev-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Corply's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Company Formation
- Incorporation
- Delaware C-Corp
- Legal Tech
- AI Agents
- MCP
- Startups
---
