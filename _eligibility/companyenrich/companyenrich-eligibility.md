---
api_specs:
- filename: companyenrich-batches-api-openapi.yml
  format: yaml
  label: CompanyEnrich Batches API
  slug: companyenrich-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companyenrich/openapi/companyenrich-batches-api-openapi.yml
- filename: companyenrich-company-bulk-enrichment-api-openapi.yml
  format: yaml
  label: CompanyEnrich Company / Bulk Enrichment API
  slug: companyenrich-company-bulk-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companyenrich/openapi/companyenrich-company-bulk-enrichment-api-openapi.yml
- filename: companyenrich-company-enrichment-api-openapi.yml
  format: yaml
  label: CompanyEnrich Company / Enrichment API
  slug: companyenrich-company-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companyenrich/openapi/companyenrich-company-enrichment-api-openapi.yml
- filename: companyenrich-company-search-api-openapi.yml
  format: yaml
  label: CompanyEnrich Company / Search API
  slug: companyenrich-company-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companyenrich/openapi/companyenrich-company-search-api-openapi.yml
- filename: companyenrich-company-search-export-api-openapi.yml
  format: yaml
  label: CompanyEnrich Company / Search Export API
  slug: companyenrich-company-search-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companyenrich/openapi/companyenrich-company-search-export-api-openapi.yml
- filename: companyenrich-geo-api-openapi.yml
  format: yaml
  label: CompanyEnrich Geo API
  slug: companyenrich-geo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companyenrich/openapi/companyenrich-geo-api-openapi.yml
- filename: companyenrich-industries-api-openapi.yml
  format: yaml
  label: CompanyEnrich Industries API
  slug: companyenrich-industries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companyenrich/openapi/companyenrich-industries-api-openapi.yml
- filename: companyenrich-keywords-api-openapi.yml
  format: yaml
  label: CompanyEnrich Keywords API
  slug: companyenrich-keywords-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companyenrich/openapi/companyenrich-keywords-api-openapi.yml
- filename: companyenrich-people-enrichment-api-openapi.yml
  format: yaml
  label: CompanyEnrich People / Enrichment API
  slug: companyenrich-people-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companyenrich/openapi/companyenrich-people-enrichment-api-openapi.yml
- filename: companyenrich-people-search-api-openapi.yml
  format: yaml
  label: CompanyEnrich People / Search API
  slug: companyenrich-people-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companyenrich/openapi/companyenrich-people-search-api-openapi.yml
- filename: companyenrich-people-search-export-api-openapi.yml
  format: yaml
  label: CompanyEnrich People / Search Export API
  slug: companyenrich-people-search-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companyenrich/openapi/companyenrich-people-search-export-api-openapi.yml
- filename: companyenrich-positions-api-openapi.yml
  format: yaml
  label: CompanyEnrich Positions API
  slug: companyenrich-positions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companyenrich/openapi/companyenrich-positions-api-openapi.yml
- filename: companyenrich-technologies-api-openapi.yml
  format: yaml
  label: CompanyEnrich Technologies API
  slug: companyenrich-technologies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companyenrich/openapi/companyenrich-technologies-api-openapi.yml
- filename: companyenrich-user-api-openapi.yml
  format: yaml
  label: CompanyEnrich User API
  slug: companyenrich-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companyenrich/openapi/companyenrich-user-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A license is granted to a single legal entity ("Licensee"), and is authorized for use solely with that entity.
    type: business
  - text: If you are a Consumer and unless the below exception applies, you have the right to cancel this Agreement and return the Product within 14 days without giving any reason.
    type: individual
  minimum_age:
    text: By using any of our Services, you agree that you are of legal age
    value: null
  restricted_uses:
  - summary: Use only for own purposes
    text: use any Services or Service Content for any purpose except for your own use
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
name: CompanyEnrich
provenance_date: '2026-11-09'
provider_name: CompanyEnrich
provider_slug: companyenrich
slug: companyenrich-eligibility
source_date: '2026-11-09'
source_filename: companyenrich-eligibility.yml
source_heading: Eligibility
source_page: https://companyenrich.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CompanyEnrich\naid: companyenrich\nurl: https://companyenrich.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: A license is granted to a single legal entity (\"Licensee\"), and is authorized for use solely with that entity.\n- type: individual\n  text: If you are a Consumer and unless the below exception applies, you have the right to cancel this Agreement\n    and return the Product within 14 days without giving any reason.\nrestricted_uses:\n- summary: Use only for own purposes\n  text: use any Services or Service\
  \ Content for any purpose except for your own use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: By using any of our Services, you agree that you are of legal age\n"
source_yaml_url: https://artifacts.apis.io/companyenrich/eligibility/companyenrich-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CompanyEnrich's own page on 2026-11-09.
synthetic: false
tags:
- Company
- B2B
- Data
- Data Enrichment
- Artificial Intelligence
---
