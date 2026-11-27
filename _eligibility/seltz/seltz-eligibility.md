---
api_specs:
- filename: seltz-answer-api-openapi.yml
  format: yaml
  label: Seltz Answer API
  slug: seltz-answer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seltz/openapi/seltz-answer-api-openapi.yml
- filename: seltz-search-api-openapi.yml
  format: yaml
  label: Seltz Search API
  slug: seltz-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seltz/openapi/seltz-search-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Special Notice for International Use: Portions of the Platform... subject to United States export controls. No portion of the Platform may be downloaded or otherwise exported or re-exported in violation of U.S. export laws.'
  entity_types:
  - text: If you are entering into this Agreement on behalf of a company, business or other legal entity, you represent that you have the authority to bind such an entity to this Agreement
    type: business
  minimum_age:
    text: Our Platform is not intended for minors under the age of 18.
    value: '18'
  restricted_uses:
  - summary: No use by minors
    text: Our Platform is not intended for minors under the age of 18.
  - summary: Free tier non-commercial only
    text: You may only use the free tier for non-commercial purposes only.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to use certain portions of the Platform, you must register an account by providing us with your name, email, and other information requested in our registration form.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Seltz
provenance_date: '2026-11-10'
provider_name: Seltz
provider_slug: seltz
slug: seltz-eligibility
source_date: '2026-11-10'
source_filename: seltz-eligibility.yml
source_heading: Eligibility
source_page: https://seltz.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Seltz\naid: seltz\nurl: https://seltz.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Special Notice for International Use: Portions of the Platform... subject to United States export controls.\n    No portion of the Platform may be downloaded or otherwise exported or re-exported in violation of U.S. export\n    laws.'\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a company, business or other legal entity, you represent\n    that you have the authority to bind such an entity to this Agreement\nrestricted_uses:\n- summary:\
  \ No use by minors\n  text: Our Platform is not intended for minors under the age of 18.\n- summary: Free tier non-commercial only\n  text: You may only use the free tier for non-commercial purposes only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to use certain portions of the Platform, you must register an account by providing us with your\n    name, email, and other information requested in our registration form.\nminimum_age:\n  value: '18'\n  text: Our Platform is not intended for minors under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/seltz/eligibility/seltz-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Seltz's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web Search
- AI Infrastructure
- Retrieval
- RAG
- Agents
- LLM
- Knowledge API
- Developer Tools
- MCP
---
