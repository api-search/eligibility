---
api_specs:
- filename: companydata-dk-account-api-openapi.yml
  format: yaml
  label: companydata.dk Account API
  slug: companydata-dk-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-account-api-openapi.yml
- filename: companydata-dk-auditors-api-openapi.yml
  format: yaml
  label: companydata.dk Auditors API
  slug: companydata-dk-auditors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-auditors-api-openapi.yml
- filename: companydata-dk-companies-api-openapi.yml
  format: yaml
  label: companydata.dk Companies API
  slug: companydata-dk-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-companies-api-openapi.yml
- filename: companydata-dk-cvrapi-dk-compatibility-api-openapi.yml
  format: yaml
  label: companydata.dk cvrapi.dk compatibility API
  slug: companydata-dk-cvrapi-dk-compatibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-cvrapi-dk-compatibility-api-openapi.yml
- filename: companydata-dk-e-invoicing-api-openapi.yml
  format: yaml
  label: companydata.dk E Invoicing API
  slug: companydata-dk-e-invoicing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-e-invoicing-api-openapi.yml
- filename: companydata-dk-legal-notices-api-openapi.yml
  format: yaml
  label: companydata.dk Legal notices API
  slug: companydata-dk-legal-notices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-legal-notices-api-openapi.yml
- filename: companydata-dk-participants-api-openapi.yml
  format: yaml
  label: companydata.dk Participants API
  slug: companydata-dk-participants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-participants-api-openapi.yml
- filename: companydata-dk-production-units-api-openapi.yml
  format: yaml
  label: companydata.dk Production Units API
  slug: companydata-dk-production-units-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-production-units-api-openapi.yml
- filename: companydata-dk-properties-api-openapi.yml
  format: yaml
  label: companydata.dk Properties API
  slug: companydata-dk-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-properties-api-openapi.yml
- filename: companydata-dk-reference-data-api-openapi.yml
  format: yaml
  label: companydata.dk Reference Data API
  slug: companydata-dk-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-reference-data-api-openapi.yml
- filename: companydata-dk-screening-api-openapi.yml
  format: yaml
  label: companydata.dk Screening API
  slug: companydata-dk-screening-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-screening-api-openapi.yml
- filename: companydata-dk-webhooks-api-openapi.yml
  format: yaml
  label: companydata.dk Webhooks API
  slug: companydata-dk-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-webhooks-api-openapi.yml
- filename: companydata-dk-working-lists-api-openapi.yml
  format: yaml
  label: companydata.dk Working Lists API
  slug: companydata-dk-working-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-dk/openapi/companydata-dk-working-lists-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Som forbruger har du som udgangspunkt 14 dages fortrydelsesret ved køb på nettet, jf. forbrugeraftaleloven.
    type: individual
  - text: Køb foretaget som led i erhverv er ikke omfattet af fortrydelsesret.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No credit data for employment
    text: Kreditoplysninger om fysiske personer (herunder indehavere af enkeltmandsvirksomheder) må ikke indhentes eller anvendes til brug for ansættelse af den pågældende.
  - summary: No direct marketing with property data
    text: Ejendomsdata må ikke bruges til direkte markedsføring over for privatpersoner
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: For at bruge visse funktioner skal du oprette en brugerkonto.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: companydata.dk
provenance_date: '2026-11-09'
provider_name: companydata.dk
provider_slug: companydata-dk
slug: companydata-dk-eligibility
source_date: '2026-11-09'
source_filename: companydata-dk-eligibility.yml
source_heading: Eligibility
source_page: https://companydata.dk/da/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: companydata.dk\naid: companydata-dk\nurl: https://companydata.dk/da/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Som forbruger har du som udgangspunkt 14 dages fortrydelsesret ved køb på nettet, jf. forbrugeraftaleloven.\n- type: business\n  text: Køb foretaget som led i erhverv er ikke omfattet af fortrydelsesret.\nrestricted_uses:\n- summary: No credit data for employment\n  text: Kreditoplysninger om fysiske personer (herunder indehavere af enkeltmandsvirksomheder) må ikke indhentes\n    eller anvendes til brug for ansættelse\
  \ af den pågældende.\n- summary: No direct marketing with property data\n  text: Ejendomsdata må ikke bruges til direkte markedsføring over for privatpersoner\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: For at bruge visse funktioner skal du oprette en brugerkonto.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/companydata-dk/eligibility/companydata-dk-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from companydata.dk's own page on 2026-11-09.
synthetic: false
tags:
- Company Data
- Business Registry
- CVR
- Denmark
- Credit Scoring
- Financial Statements
- Lead Generation
- MCP
- REST API
---
