---
api_specs:
- filename: getminds-agent-runs-api-openapi.yml
  format: yaml
  label: Minds Agent Runs API
  slug: getminds-agent-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getminds/openapi/getminds-agent-runs-api-openapi.yml
- filename: getminds-api-keys-api-openapi.yml
  format: yaml
  label: Minds API Keys API
  slug: getminds-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getminds/openapi/getminds-api-keys-api-openapi.yml
- filename: getminds-audiences-api-openapi.yml
  format: yaml
  label: Minds Audiences API
  slug: getminds-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getminds/openapi/getminds-audiences-api-openapi.yml
- filename: getminds-auth-api-openapi.yml
  format: yaml
  label: Minds Auth API
  slug: getminds-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getminds/openapi/getminds-auth-api-openapi.yml
- filename: getminds-chat-api-openapi.yml
  format: yaml
  label: Minds Chat API
  slug: getminds-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getminds/openapi/getminds-chat-api-openapi.yml
- filename: getminds-knowledge-api-openapi.yml
  format: yaml
  label: Minds Knowledge API
  slug: getminds-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getminds/openapi/getminds-knowledge-api-openapi.yml
- filename: getminds-meta-api-openapi.yml
  format: yaml
  label: Minds Meta API
  slug: getminds-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getminds/openapi/getminds-meta-api-openapi.yml
- filename: getminds-minds-api-openapi.yml
  format: yaml
  label: Minds Minds API
  slug: getminds-minds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getminds/openapi/getminds-minds-api-openapi.yml
- filename: getminds-models-api-openapi.yml
  format: yaml
  label: Minds Models API
  slug: getminds-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getminds/openapi/getminds-models-api-openapi.yml
- filename: getminds-research-api-openapi.yml
  format: yaml
  label: Minds Research API
  slug: getminds-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getminds/openapi/getminds-research-api-openapi.yml
- filename: getminds-studies-api-openapi.yml
  format: yaml
  label: Minds Studies API
  slug: getminds-studies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getminds/openapi/getminds-studies-api-openapi.yml
- filename: getminds-study-drafts-api-openapi.yml
  format: yaml
  label: Minds Study Drafts API
  slug: getminds-study-drafts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getminds/openapi/getminds-study-drafts-api-openapi.yml
- filename: getminds-study-runs-api-openapi.yml
  format: yaml
  label: Minds Study Runs API
  slug: getminds-study-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getminds/openapi/getminds-study-runs-api-openapi.yml
- filename: getminds-study-templates-api-openapi.yml
  format: yaml
  label: Minds Study Templates API
  slug: getminds-study-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getminds/openapi/getminds-study-templates-api-openapi.yml
- filename: getminds-acp-api-openapi.yml
  format: yaml
  label: Minds ACP API
  slug: getminds-acp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getminds/openapi/getminds-acp-api-openapi.yml
- filename: getminds-billing-api-openapi.yml
  format: yaml
  label: Minds Billing API
  slug: getminds-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getminds/openapi/getminds-billing-api-openapi.yml
- filename: getminds-events-api-openapi.yml
  format: yaml
  label: Minds Events API
  slug: getminds-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getminds/openapi/getminds-events-api-openapi.yml
- filename: getminds-integrations-api-openapi.yml
  format: yaml
  label: Minds Integrations API
  slug: getminds-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getminds/openapi/getminds-integrations-api-openapi.yml
- filename: getminds-support-api-openapi.yml
  format: yaml
  label: Minds Support API
  slug: getminds-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getminds/openapi/getminds-support-api-openapi.yml
- filename: getminds-uploads-api-openapi.yml
  format: yaml
  label: Minds Uploads API
  slug: getminds-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getminds/openapi/getminds-uploads-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The services are designed primarily for entrepreneurs, companies, public bodies, and other customers acting in a commercial or independent professional capacity
    type: business
  - text: If a natural person obtains the services mainly for purposes outside their trade, business, or profession, that person is a consumer
    type: individual
  minimum_age:
    text: Users must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: High-impact decisions without oversight
    text: the Customer must not use an output as the sole or determinative basis for a decision that produces legal or similarly significant effects for a natural person.
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
name: Minds
provenance_date: '2026-11-09'
provider_name: Minds
provider_slug: getminds
slug: getminds-eligibility
source_date: '2026-11-09'
source_filename: getminds-eligibility.yml
source_heading: Eligibility
source_page: https://getminds.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Minds\naid: getminds\nurl: https://getminds.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The services are designed primarily for entrepreneurs, companies, public bodies, and other customers acting\n    in a commercial or independent professional capacity\n- type: individual\n  text: If a natural person obtains the services mainly for purposes outside their trade, business, or profession,\n    that person is a consumer\nrestricted_uses:\n- summary: High-impact decisions without oversight\n  text: the Customer must not\
  \ use an output as the sole or determinative basis for a decision that produces legal\n    or similarly significant effects for a natural person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Users must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/getminds/eligibility/getminds-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Minds's own page on 2026-11-09.
synthetic: false
tags:
- Synthetic Research
- Market Research
- Surveys
- User Research
- Marketing Analytics
- ai-personas
- MCP
- Agent-Native
- GDPR
---
