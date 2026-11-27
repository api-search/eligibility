---
api_specs:
- filename: stipple-sh-agent-card-json-api-openapi.yml
  format: yaml
  label: stipple-sh Agent Card.json API
  slug: stipple-sh-agent-card-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stipple-sh/openapi/stipple-sh-agent-card-json-api-openapi.yml
- filename: stipple-sh-agent-json-api-openapi.yml
  format: yaml
  label: stipple-sh Agent.json API
  slug: stipple-sh-agent-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stipple-sh/openapi/stipple-sh-agent-json-api-openapi.yml
- filename: stipple-sh-agents-md-api-openapi.yml
  format: yaml
  label: stipple-sh Agents.md API
  slug: stipple-sh-agents-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stipple-sh/openapi/stipple-sh-agents-md-api-openapi.yml
- filename: stipple-sh-auth-api-openapi.yml
  format: yaml
  label: stipple-sh Auth API
  slug: stipple-sh-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stipple-sh/openapi/stipple-sh-auth-api-openapi.yml
- filename: stipple-sh-bids-api-openapi.yml
  format: yaml
  label: stipple-sh Bids API
  slug: stipple-sh-bids-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stipple-sh/openapi/stipple-sh-bids-api-openapi.yml
- filename: stipple-sh-companies-api-openapi.yml
  format: yaml
  label: stipple-sh Companies API
  slug: stipple-sh-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stipple-sh/openapi/stipple-sh-companies-api-openapi.yml
- filename: stipple-sh-health-api-openapi.yml
  format: yaml
  label: stipple-sh Health API
  slug: stipple-sh-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stipple-sh/openapi/stipple-sh-health-api-openapi.yml
- filename: stipple-sh-healthz-api-openapi.yml
  format: yaml
  label: stipple-sh Healthz API
  slug: stipple-sh-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stipple-sh/openapi/stipple-sh-healthz-api-openapi.yml
- filename: stipple-sh-keys-usage-api-openapi.yml
  format: yaml
  label: stipple-sh Keys & usage API
  slug: stipple-sh-keys-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stipple-sh/openapi/stipple-sh-keys-usage-api-openapi.yml
- filename: stipple-sh-livez-api-openapi.yml
  format: yaml
  label: stipple-sh Livez API
  slug: stipple-sh-livez-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stipple-sh/openapi/stipple-sh-livez-api-openapi.yml
- filename: stipple-sh-llms-txt-api-openapi.yml
  format: yaml
  label: stipple-sh Llms.txt API
  slug: stipple-sh-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stipple-sh/openapi/stipple-sh-llms-txt-api-openapi.yml
- filename: stipple-sh-meta-api-openapi.yml
  format: yaml
  label: stipple-sh Meta API
  slug: stipple-sh-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stipple-sh/openapi/stipple-sh-meta-api-openapi.yml
- filename: stipple-sh-orgs-api-openapi.yml
  format: yaml
  label: stipple-sh Orgs API
  slug: stipple-sh-orgs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stipple-sh/openapi/stipple-sh-orgs-api-openapi.yml
- filename: stipple-sh-tenders-api-openapi.yml
  format: yaml
  label: stipple-sh Tenders API
  slug: stipple-sh-tenders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stipple-sh/openapi/stipple-sh-tenders-api-openapi.yml
- filename: stipple-sh-well-known-api-openapi.yml
  format: yaml
  label: stipple-sh .well Known API
  slug: stipple-sh-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stipple-sh/openapi/stipple-sh-well-known-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful purpose
    text: use the service for an unlawful purpose
  - summary: False or misleading buyer responses
    text: send a buyer a response you know to be false or misleading
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in with an emailed link or Google. API keys need an account. Both are free.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: stipple-sh
provenance_date: '2026-11-10'
provider_name: stipple-sh
provider_slug: stipple-sh
slug: stipple-sh-eligibility
source_date: '2026-11-10'
source_filename: stipple-sh-eligibility.yml
source_heading: Eligibility
source_page: https://www.stipple.sh/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: stipple-sh\naid: stipple-sh\nurl: https://www.stipple.sh/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful purpose\n  text: use the service for an unlawful purpose\n- summary: False or misleading buyer responses\n  text: send a buyer a response you know to be false or misleading\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You sign in with an emailed link or Google. API keys need an account. Both are free.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/stipple-sh/eligibility/stipple-sh-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 3 quoted statements, read from stipple-sh's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Government
- Procurement
- Tenders
- Australia
- Grants
---
