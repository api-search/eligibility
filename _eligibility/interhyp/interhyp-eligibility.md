---
api_specs:
- filename: interhyp-commands-api-openapi.yml
  format: yaml
  label: Interhyp Commands API
  slug: interhyp-commands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/interhyp/openapi/interhyp-commands-api-openapi.yml
- filename: interhyp-documents-api-openapi.yml
  format: yaml
  label: Interhyp Documents API
  slug: interhyp-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/interhyp/openapi/interhyp-documents-api-openapi.yml
- filename: interhyp-financing-application-api-openapi.yml
  format: yaml
  label: Interhyp Financing Application API
  slug: interhyp-financing-application-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/interhyp/openapi/interhyp-financing-application-api-openapi.yml
- filename: interhyp-info-api-openapi.yml
  format: yaml
  label: Interhyp Info API
  slug: interhyp-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/interhyp/openapi/interhyp-info-api-openapi.yml
- filename: interhyp-logbook-api-openapi.yml
  format: yaml
  label: Interhyp Logbook API
  slug: interhyp-logbook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/interhyp/openapi/interhyp-logbook-api-openapi.yml
- filename: interhyp-pre-submission-checks-api-openapi.yml
  format: yaml
  label: Interhyp Pre Submission Checks API
  slug: interhyp-pre-submission-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/interhyp/openapi/interhyp-pre-submission-checks-api-openapi.yml
- filename: interhyp-protocol-api-openapi.yml
  format: yaml
  label: Interhyp Protocol API
  slug: interhyp-protocol-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/interhyp/openapi/interhyp-protocol-api-openapi.yml
- filename: interhyp-submissions-api-openapi.yml
  format: yaml
  label: Interhyp Submissions API
  slug: interhyp-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/interhyp/openapi/interhyp-submissions-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Diese Vereinbarung gilt nur für gewerbsmäßige Nutzer. Der Nutzer ist Unternehmer im Sinne des § 14 BGB.
    type: business
  minimum_age:
    text: null
    value: null
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
name: Interhyp
provenance_date: '2026-11-09'
provider_name: Interhyp
provider_slug: interhyp
slug: interhyp-eligibility
source_date: '2026-11-09'
source_filename: interhyp-eligibility.yml
source_heading: Eligibility
source_page: https://developer.ehyphome.de/assets/AGB.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Interhyp\naid: interhyp\nurl: https://developer.ehyphome.de/assets/AGB.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Diese Vereinbarung gilt nur für gewerbsmäßige Nutzer. Der Nutzer ist Unternehmer im Sinne des § 14 BGB.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/interhyp/eligibility/interhyp-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Interhyp's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Mortgage
- Lending
- Baufinanzierung
- Real Estate
- Banking
- Germany
- API-First
---
