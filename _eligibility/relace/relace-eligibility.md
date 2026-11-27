---
api_specs:
- filename: relace-code-api-openapi.yml
  format: yaml
  label: Relace Code API
  slug: relace-code-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relace/openapi/relace-code-api-openapi.yml
- filename: relace-repo-api-openapi.yml
  format: yaml
  label: Relace Repo API
  slug: relace-repo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relace/openapi/relace-repo-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are registering as a business entity, you personally guarantee that you have the authority to agree to these Terms of Use on behalf of the business.
    type: business
  minimum_age:
    text: Use the Services if you are under the age of 18 or otherwise unable to enter into binding legal agreements
    value: '18'
  restricted_uses:
  - summary: Unlawful or fraudulent use
    text: Use the Services unlawfully or for an unlawful purpose
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
name: Relace
provenance_date: '2026-11-10'
provider_name: Relace
provider_slug: relace
slug: relace-eligibility
source_date: '2026-11-10'
source_filename: relace-eligibility.yml
source_heading: Eligibility
source_page: https://relace.ai/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Relace\naid: relace\nurl: https://relace.ai/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are registering as a business entity, you personally guarantee that you have the authority to agree\n    to these Terms of Use on behalf of the business.\nrestricted_uses:\n- summary: Unlawful or fraudulent use\n  text: Use the Services unlawfully or for an unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Use the Services if you are\
  \ under the age of 18 or otherwise unable to enter into binding legal agreements\n"
source_yaml_url: https://artifacts.apis.io/relace/eligibility/relace-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Relace's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Coding Agents
- Code Generation
- Developer Tools
- Machine Learning
- Code Search
- LLM
- Foundation Models
---
