---
api_specs:
- filename: synlake-ai-auth-api-openapi.yml
  format: yaml
  label: synlake-ai Auth API
  slug: synlake-ai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synlake-ai/openapi/synlake-ai-auth-api-openapi.yml
- filename: synlake-ai-billing-api-openapi.yml
  format: yaml
  label: synlake-ai Billing API
  slug: synlake-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synlake-ai/openapi/synlake-ai-billing-api-openapi.yml
- filename: synlake-ai-catalog-api-openapi.yml
  format: yaml
  label: synlake-ai Catalog API
  slug: synlake-ai-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synlake-ai/openapi/synlake-ai-catalog-api-openapi.yml
- filename: synlake-ai-execution-api-openapi.yml
  format: yaml
  label: synlake-ai Execution API
  slug: synlake-ai-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synlake-ai/openapi/synlake-ai-execution-api-openapi.yml
- filename: synlake-ai-infrastructure-api-openapi.yml
  format: yaml
  label: synlake-ai Infrastructure API
  slug: synlake-ai-infrastructure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synlake-ai/openapi/synlake-ai-infrastructure-api-openapi.yml
- filename: synlake-ai-system-api-openapi.yml
  format: yaml
  label: synlake-ai System API
  slug: synlake-ai-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synlake-ai/openapi/synlake-ai-system-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using Synlake on behalf of an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Violating law or abusive use
    text: 'You may not use Synlake to: (a) violate any law, (b) attempt to reverse-engineer, scrape, or resell the API data, (c) exceed rate limits through automated circumvention, or (d) submit malicious or abusive requests.'
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
name: synlake-ai
provenance_date: '2026-11-10'
provider_name: synlake-ai
provider_slug: synlake-ai
slug: synlake-ai-eligibility
source_date: '2026-11-10'
source_filename: synlake-ai-eligibility.yml
source_heading: Eligibility
source_page: https://synlake.ai/legal/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: synlake-ai\naid: synlake-ai\nurl: https://synlake.ai/legal/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using Synlake on behalf of an organization, you represent that you have authority to bind that\n    organization.\nrestricted_uses:\n- summary: Violating law or abusive use\n  text: 'You may not use Synlake to: (a) violate any law, (b) attempt to reverse-engineer, scrape, or resell the\n    API data, (c) exceed rate limits through automated circumvention, or (d) submit malicious or abusive requests.'\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/synlake-ai/eligibility/synlake-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from synlake-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data Infrastructure
- AI Agents
- Cloud
- Terraform
---
