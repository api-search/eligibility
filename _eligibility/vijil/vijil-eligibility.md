---
api_specs:
- filename: vijil-agent-environment-api-openapi.yml
  format: yaml
  label: Vijil Agent Environment API
  slug: vijil-agent-environment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vijil/openapi/vijil-agent-environment-api-openapi.yml
- filename: vijil-diamond-api-openapi.yml
  format: yaml
  label: Vijil Diamond API
  slug: vijil-diamond-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vijil/openapi/vijil-diamond-api-openapi.yml
- filename: vijil-dome-api-openapi.yml
  format: yaml
  label: Vijil Dome API
  slug: vijil-dome-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vijil/openapi/vijil-dome-api-openapi.yml
- filename: vijil-red-team-api-openapi.yml
  format: yaml
  label: Vijil Red Team API
  slug: vijil-red-team-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vijil/openapi/vijil-red-team-api-openapi.yml
- filename: vijil-teams-api-openapi.yml
  format: yaml
  label: Vijil Teams API
  slug: vijil-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vijil/openapi/vijil-teams-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Site and Services are controlled, operated and administered by Vijil from our offices within the USA.
  entity_types:
  - text: If you are acting on behalf of your employer or legal entity, you represent that you are authorized to bind your employer or legal entity to these Terms.
    type: business
  minimum_age:
    text: Vijil does not knowingly collect, either online or offline, personal information from persons under the age of thirteen. If you are under 18, you may use vijil.ai only with permission of a parent or guardian.
    value: '13'
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: you will not use the Site or Services for any purpose that is unlawful or prohibited by these Terms.
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
name: Vijil
provenance_date: '2026-11-10'
provider_name: Vijil
provider_slug: vijil
slug: vijil-eligibility
source_date: '2026-11-10'
source_filename: vijil-eligibility.yml
source_heading: Eligibility
source_page: https://www.vijil.ai/policies/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vijil\naid: vijil\nurl: https://www.vijil.ai/policies/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Site and Services are controlled, operated and administered by Vijil from our offices within the USA.\nentity_types:\n- type: business\n  text: If you are acting on behalf of your employer or legal entity, you represent that you are authorized to bind\n    your employer or legal entity to these Terms.\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: you will not use the Site or Services for any purpose that is unlawful or prohibited by these\
  \ Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Vijil does not knowingly collect, either online or offline, personal information from persons under the\n    age of thirteen. If you are under 18, you may use vijil.ai only with permission of a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/vijil/eligibility/vijil-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Vijil's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Agent Security
- AI Safety
- Trust
- Red Teaming
- Guardrails
- LLM Security
- Evaluation
- Observability
- MCP
---
