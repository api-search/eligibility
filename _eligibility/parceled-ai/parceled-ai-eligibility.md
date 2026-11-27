---
api_specs:
- filename: parceled-ai-account-api-openapi.yml
  format: yaml
  label: parceled-ai Account API
  slug: parceled-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parceled-ai/openapi/parceled-ai-account-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old, or the age of majority in your jurisdiction, to create an account.
    type: individual
  - text: If you are agreeing on behalf of an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age of majority in your jurisdiction, to create an account.
    value: '18'
  restricted_uses:
  - summary: Unlawful or non-compliant use of property-owner data
    text: You are solely responsible for complying with all applicable laws governing the use of that data in your jurisdiction and the jurisdictions of the properties you query
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
name: parceled-ai
provenance_date: '2026-11-10'
provider_name: parceled-ai
provider_slug: parceled-ai
slug: parceled-ai-eligibility
source_date: '2026-11-10'
source_filename: parceled-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.parceled.ai/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: parceled-ai\naid: parceled-ai\nurl: https://www.parceled.ai/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of majority in your jurisdiction, to create an account.\n- type: business\n  text: If you are agreeing on behalf of an organization, you represent that you have authority to bind that organization.\nrestricted_uses:\n- summary: Unlawful or non-compliant use of property-owner data\n  text: You are solely responsible for complying with all applicable laws governing the use of that\
  \ data in your\n    jurisdiction and the jurisdictions of the properties you query\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority in your jurisdiction, to create an account.\n"
source_yaml_url: https://artifacts.apis.io/parceled-ai/eligibility/parceled-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from parceled-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Data API
- Mapping
- Artificial Intelligence
---
