---
api_specs:
- filename: sentisense-ai-openapi-generated.yml
  format: yaml
  label: sentisense-ai API
  slug: sentisense-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sentisense-ai/openapi/_ae-authored/sentisense-ai-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Platform if you are located in a country subject to U.S. embargo or have been designated as a prohibited party.
  entity_types:
  - text: You must be at least 18 years old to use the Platform.
    type: individual
  - text: If you are using the Platform on behalf of an organization, you represent and warrant that you have the authority to bind that organization to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Platform.
    value: '18'
  restricted_uses:
  - summary: Investment advice reliance
    text: Nothing on the Platform constitutes investment advice, recommendations, or an offer to buy or sell securities.
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
name: sentisense-ai
provenance_date: '2026-11-10'
provider_name: sentisense-ai
provider_slug: sentisense-ai
slug: sentisense-ai-eligibility
source_date: '2026-11-10'
source_filename: sentisense-ai-eligibility.yml
source_heading: Eligibility
source_page: https://sentisense.ai/agreement/Terms-of-Service.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: sentisense-ai\naid: sentisense-ai\nurl: https://sentisense.ai/agreement/Terms-of-Service.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Platform if you are located in a country subject to U.S. embargo or have been designated\n    as a prohibited party.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Platform.\n- type: business\n  text: If you are using the Platform on behalf of an organization, you represent and warrant that you have the\n    authority to bind that organization to these Terms\nrestricted_uses:\n- summary:\
  \ Investment advice reliance\n  text: Nothing on the Platform constitutes investment advice, recommendations, or an offer to buy or sell securities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/sentisense-ai/eligibility/sentisense-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from sentisense-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Analytics
- Machine Learning
- Enterprise
---
