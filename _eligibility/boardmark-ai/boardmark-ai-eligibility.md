---
api_specs:
- filename: boardmark-ai-openapi-generated.yml
  format: yaml
  label: BoardMark API
  slug: boardmark-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boardmark-ai/openapi/_ae-authored/boardmark-ai-openapi-generated.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Individuals (consumers) resident in the European Union cannot subscribe to a paid plan at present; they may use the Service free of charge within the conditions in section 8.
  entity_types:
  - text: '"Customer company": a Customer''s workspace in the Service, either individual (one member only) or juristic.'
    type: individual
  - text: A Customer company established in the European Union must give its valid VAT identification number (VAT ID) in its tax details before using a paid plan
    type: business
  minimum_age:
    text: You must be of legal age and have legal capacity to enter into contracts.
    value: legal age
  restricted_uses:
  - summary: Unlawful use
    text: use the Service for anything unlawful or to infringe the rights of others
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Going beyond this, or upgrading to the Premium plan, requires a payment method, complete tax details and a verified email first.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BoardMark
provenance_date: '2026-11-09'
provider_name: BoardMark
provider_slug: boardmark-ai
slug: boardmark-ai-eligibility
source_date: '2026-11-09'
source_filename: boardmark-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.boardmark.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BoardMark\naid: boardmark-ai\nurl: https://www.boardmark.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Individuals (consumers) resident in the European Union cannot subscribe to a paid plan at present; they\n    may use the Service free of charge within the conditions in section 8.\nentity_types:\n- type: individual\n  text: '\"Customer company\": a Customer''s workspace in the Service, either individual (one member only) or juristic.'\n- type: business\n  text: A Customer company established in the European Union must give its valid VAT identification number (VAT\n\
  \    ID) in its tax details before using a paid plan\nrestricted_uses:\n- summary: Unlawful use\n  text: use the Service for anything unlawful or to infringe the rights of others\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Going beyond this, or upgrading to the Premium plan, requires a payment method, complete tax details and\n    a verified email first.\nminimum_age:\n  value: legal age\n  text: You must be of legal age and have legal capacity to enter into contracts.\n"
source_yaml_url: https://artifacts.apis.io/boardmark-ai/eligibility/boardmark-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from BoardMark's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Project Management
- Artificial Intelligence
- Collaboration
---
