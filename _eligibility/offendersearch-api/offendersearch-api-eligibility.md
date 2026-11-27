---
api_specs:
- filename: offendersearch-api-account-api-openapi.yml
  format: yaml
  label: Offendersearch API Account API
  slug: offendersearch-api-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/offendersearch-api/openapi/offendersearch-api-account-api-openapi.yml
- filename: offendersearch-api-admin-api-openapi.yml
  format: yaml
  label: Offendersearch API Admin API
  slug: offendersearch-api-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/offendersearch-api/openapi/offendersearch-api-admin-api-openapi.yml
- filename: offendersearch-api-auth-api-openapi.yml
  format: yaml
  label: Offendersearch API Auth API
  slug: offendersearch-api-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/offendersearch-api/openapi/offendersearch-api-auth-api-openapi.yml
- filename: offendersearch-api-batch-api-openapi.yml
  format: yaml
  label: Offendersearch API Batch API
  slug: offendersearch-api-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/offendersearch-api/openapi/offendersearch-api-batch-api-openapi.yml
- filename: offendersearch-api-billing-api-openapi.yml
  format: yaml
  label: Offendersearch API Billing API
  slug: offendersearch-api-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/offendersearch-api/openapi/offendersearch-api-billing-api-openapi.yml
- filename: offendersearch-api-compat-api-openapi.yml
  format: yaml
  label: Offendersearch API Compat API
  slug: offendersearch-api-compat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/offendersearch-api/openapi/offendersearch-api-compat-api-openapi.yml
- filename: offendersearch-api-keys-api-openapi.yml
  format: yaml
  label: Offendersearch API Keys API
  slug: offendersearch-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/offendersearch-api/openapi/offendersearch-api-keys-api-openapi.yml
- filename: offendersearch-api-proof-docs-api-openapi.yml
  format: yaml
  label: Offendersearch API Proof Docs API
  slug: offendersearch-api-proof-docs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/offendersearch-api/openapi/offendersearch-api-proof-docs-api-openapi.yml
- filename: offendersearch-api-records-api-openapi.yml
  format: yaml
  label: Offendersearch API Records API
  slug: offendersearch-api-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/offendersearch-api/openapi/offendersearch-api-records-api-openapi.yml
- filename: offendersearch-api-report-api-openapi.yml
  format: yaml
  label: Offendersearch API Report API
  slug: offendersearch-api-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/offendersearch-api/openapi/offendersearch-api-report-api-openapi.yml
- filename: offendersearch-api-search-api-openapi.yml
  format: yaml
  label: Offendersearch API Search API
  slug: offendersearch-api-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/offendersearch-api/openapi/offendersearch-api-search-api-openapi.yml
- filename: offendersearch-api-searches-api-openapi.yml
  format: yaml
  label: Offendersearch API Searches API
  slug: offendersearch-api-searches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/offendersearch-api/openapi/offendersearch-api-searches-api-openapi.yml
- filename: offendersearch-api-sources-api-openapi.yml
  format: yaml
  label: Offendersearch API Sources API
  slug: offendersearch-api-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/offendersearch-api/openapi/offendersearch-api-sources-api-openapi.yml
- filename: offendersearch-api-support-api-openapi.yml
  format: yaml
  label: Offendersearch API Support API
  slug: offendersearch-api-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/offendersearch-api/openapi/offendersearch-api-support-api-openapi.yml
- filename: offendersearch-api-team-api-openapi.yml
  format: yaml
  label: Offendersearch API Team API
  slug: offendersearch-api-team-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/offendersearch-api/openapi/offendersearch-api-team-api-openapi.yml
- filename: offendersearch-api-usage-api-openapi.yml
  format: yaml
  label: Offendersearch API Usage API
  slug: offendersearch-api-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/offendersearch-api/openapi/offendersearch-api-usage-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: a separately enabled service for approved consumer reporting agencies and screening platforms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No sole basis for adverse action
    text: use the API Data as the sole basis for any adverse action against an individual (see §5);
  - summary: No harassment or discrimination
    text: You must not use registry information to harass, intimidate, threaten, or discriminate against a registrant or their family, or to commit a crime.
  - summary: No PHI without BAA
    text: You must not submit protected health information (PHI/ePHI) unless you and OffenderSearch have an executed Business Associate Agreement (BAA).
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: a separately enabled service for approved consumer reporting agencies and screening platforms, under a separate written FCRA agreement
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Offendersearch API
provenance_date: '2026-11-10'
provider_name: Offendersearch API
provider_slug: offendersearch-api
slug: offendersearch-api-eligibility
source_date: '2026-11-10'
source_filename: offendersearch-api-eligibility.yml
source_heading: Eligibility
source_page: https://offendersearch.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Offendersearch API\naid: offendersearch-api\nurl: https://offendersearch.app/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: a separately enabled service for approved consumer reporting agencies and screening platforms\nrestricted_uses:\n- summary: No sole basis for adverse action\n  text: use the API Data as the sole basis for any adverse action against an individual (see §5);\n- summary: No harassment or discrimination\n  text: You must not use registry information to harass, intimidate, threaten, or discriminate against a registrant\n\
  \    or their family, or to commit a crime.\n- summary: No PHI without BAA\n  text: You must not submit protected health information (PHI/ePHI) unless you and OffenderSearch have an executed\n    Business Associate Agreement (BAA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: a separately enabled service for approved consumer reporting agencies and screening platforms, under a separate\n    written FCRA agreement\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/offendersearch-api/eligibility/offendersearch-api-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Offendersearch API's own page on 2026-11-10.
synthetic: false
tags:
- Background Checks
- Identity Verification
- Public Records
- Criminal Records
- Compliance
- Trust and Safety
- Human Resources
- Recruiting
- PropTech
- Tenant Screening
- healthcare-screening
- Data API
- MCP Server
- Agent-Native
---
