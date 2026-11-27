---
api_specs:
- filename: globaldatabase-com-autocomplete-api-openapi.yml
  format: yaml
  label: Global Database Autocomplete API
  slug: globaldatabase-com-autocomplete-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/globaldatabase-com/openapi/globaldatabase-com-autocomplete-api-openapi.yml
- filename: globaldatabase-com-company-by-linkedin-api-openapi.yml
  format: yaml
  label: Global Database Company By Linkedin API
  slug: globaldatabase-com-company-by-linkedin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/globaldatabase-com/openapi/globaldatabase-com-company-by-linkedin-api-openapi.yml
- filename: globaldatabase-com-company-by-url-api-openapi.yml
  format: yaml
  label: Global Database Company By Url API
  slug: globaldatabase-com-company-by-url-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/globaldatabase-com/openapi/globaldatabase-com-company-by-url-api-openapi.yml
- filename: globaldatabase-com-company-details-api-openapi.yml
  format: yaml
  label: Global Database Company Details API
  slug: globaldatabase-com-company-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/globaldatabase-com/openapi/globaldatabase-com-company-details-api-openapi.yml
- filename: globaldatabase-com-company-financials-api-openapi.yml
  format: yaml
  label: Global Database Company Financials API
  slug: globaldatabase-com-company-financials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/globaldatabase-com/openapi/globaldatabase-com-company-financials-api-openapi.yml
- filename: globaldatabase-com-company-ownership-api-openapi.yml
  format: yaml
  label: Global Database Company Ownership API
  slug: globaldatabase-com-company-ownership-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/globaldatabase-com/openapi/globaldatabase-com-company-ownership-api-openapi.yml
- filename: globaldatabase-com-fastapi-api-openapi.yml
  format: yaml
  label: Global Database Fast API
  slug: globaldatabase-com-fastapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/globaldatabase-com/openapi/globaldatabase-com-fastapi-api-openapi.yml
- filename: globaldatabase-com-health-api-openapi.yml
  format: yaml
  label: Global Database Health API
  slug: globaldatabase-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/globaldatabase-com/openapi/globaldatabase-com-health-api-openapi.yml
- filename: globaldatabase-com-nomenclature-api-openapi.yml
  format: yaml
  label: Global Database Nomenclature API
  slug: globaldatabase-com-nomenclature-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/globaldatabase-com/openapi/globaldatabase-com-nomenclature-api-openapi.yml
- filename: globaldatabase-com-oauth-api-openapi.yml
  format: yaml
  label: Global Database OAuth API
  slug: globaldatabase-com-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/globaldatabase-com/openapi/globaldatabase-com-oauth-api-openapi.yml
- filename: globaldatabase-com-playground-api-openapi.yml
  format: yaml
  label: Global Database Playground API
  slug: globaldatabase-com-playground-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/globaldatabase-com/openapi/globaldatabase-com-playground-api-openapi.yml
- filename: globaldatabase-com-prospecting-api-openapi.yml
  format: yaml
  label: Global Database Prospecting API
  slug: globaldatabase-com-prospecting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/globaldatabase-com/openapi/globaldatabase-com-prospecting-api-openapi.yml
- filename: globaldatabase-com-verify-token-api-openapi.yml
  format: yaml
  label: Global Database Verify Token API
  slug: globaldatabase-com-verify-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/globaldatabase-com/openapi/globaldatabase-com-verify-token-api-openapi.yml
- filename: globaldatabase-com-well-known-api-openapi.yml
  format: yaml
  label: Global Database .well Known API
  slug: globaldatabase-com-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/globaldatabase-com/openapi/globaldatabase-com-well-known-api-openapi.yml
- filename: globaldatabase-com-osb-api-openapi.yml
  format: yaml
  label: Global Database Osb API
  slug: globaldatabase-com-osb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/globaldatabase-com/openapi/globaldatabase-com-osb-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are offered exclusively to business users; the Services are not intended for, and must not be used by, consumers.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: unlawful or fraudulent use
    text: use the Services for any unlawful, fraudulent, deceptive or harmful purpose
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
name: Global Database
provenance_date: '2026-11-09'
provider_name: Global Database
provider_slug: globaldatabase-com
slug: globaldatabase-com-eligibility
source_date: '2026-11-09'
source_filename: globaldatabase-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.globaldatabase.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Global Database\naid: globaldatabase-com\nurl: https://www.globaldatabase.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are offered exclusively to business users; the Services are not intended for, and must not\n    be used by, consumers.\nrestricted_uses:\n- summary: unlawful or fraudulent use\n  text: use the Services for any unlawful, fraudulent, deceptive or harmful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/globaldatabase-com/eligibility/globaldatabase-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Global Database's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Company Data
- KYB
- Compliance
- Business Verification
- Beneficial Ownership
- Finance
- Credit Risk
- Data Enrichment
- Prospecting
- Webhook
- MCP
- AI Agents
- United Kingdom
---
