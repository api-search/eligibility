---
api_specs:
- filename: companydata-com-company-api-openapi.yml
  format: yaml
  label: CompanyData Company API
  slug: companydata-com-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-com/openapi/companydata-com-company-api-openapi.yml
- filename: companydata-com-corporate-structure-api-openapi.yml
  format: yaml
  label: CompanyData Corporate Structure API
  slug: companydata-com-corporate-structure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-com/openapi/companydata-com-corporate-structure-api-openapi.yml
- filename: companydata-com-domain-enrichment-api-openapi.yml
  format: yaml
  label: CompanyData Domain Enrichment API
  slug: companydata-com-domain-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-com/openapi/companydata-com-domain-enrichment-api-openapi.yml
- filename: companydata-com-lookup-api-openapi.yml
  format: yaml
  label: CompanyData Lookup API
  slug: companydata-com-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-com/openapi/companydata-com-lookup-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Client is not permitted to take the Work or use it outside the Netherlands, unless explicitly agreed otherwise.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Limited direct marketing contact
    text: the Client may only use the data/information to make contact once with a private individual/natural person in connection with one direct marketing campaign
  - summary: Contact window
    text: the contact as described in this article may not be made later than within 6 weeks after the Agreement has been concluded.
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
name: CompanyData
provenance_date: '2026-11-09'
provider_name: CompanyData
provider_slug: companydata-com
slug: companydata-com-eligibility
source_date: '2026-11-09'
source_filename: companydata-com-eligibility.yml
source_heading: Eligibility
source_page: https://companydata.com/bold-platform-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CompanyData\naid: companydata-com\nurl: https://companydata.com/bold-platform-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Client is not permitted to take the Work or use it outside the Netherlands, unless explicitly agreed\n    otherwise.\nentity_types: []\nrestricted_uses:\n- summary: Limited direct marketing contact\n  text: the Client may only use the data/information to make contact once with a private individual/natural person\n    in connection with one direct marketing campaign\n- summary: Contact window\n  text: the contact as described in this article may\
  \ not be made later than within 6 weeks after the Agreement has\n    been concluded.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/companydata-com/eligibility/companydata-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from CompanyData's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Company Data
- Business Registry
- B2B Data
- Data Enrichment
- KYC
- KYB
- Lead Generation
- MCP
---
