---
api_specs:
- filename: uplead-account-api-openapi.yml
  format: yaml
  label: UpLead Account API
  slug: uplead-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplead/openapi/uplead-account-api-openapi.yml
- filename: uplead-combined-api-openapi.yml
  format: yaml
  label: UpLead Combined API
  slug: uplead-combined-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplead/openapi/uplead-combined-api-openapi.yml
- filename: uplead-company-api-openapi.yml
  format: yaml
  label: UpLead Company API
  slug: uplead-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplead/openapi/uplead-company-api-openapi.yml
- filename: uplead-lists-api-openapi.yml
  format: yaml
  label: UpLead Lists API
  slug: uplead-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplead/openapi/uplead-lists-api-openapi.yml
- filename: uplead-person-api-openapi.yml
  format: yaml
  label: UpLead Person API
  slug: uplead-person-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplead/openapi/uplead-person-api-openapi.yml
- filename: uplead-prospector-api-openapi.yml
  format: yaml
  label: UpLead Prospector API
  slug: uplead-prospector-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplead/openapi/uplead-prospector-api-openapi.yml
- filename: uplead-reference-api-openapi.yml
  format: yaml
  label: UpLead Reference API
  slug: uplead-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplead/openapi/uplead-reference-api-openapi.yml
- filename: uplead-search-api-openapi.yml
  format: yaml
  label: UpLead Search API
  slug: uplead-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplead/openapi/uplead-search-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: UpLead is based in the United States. We make no claims that the Subscription Services, Product, or the Website or any of their content is accessible or appropriate outside of the United States.
  entity_types:
  - text: If Customer is entering into these License Terms on behalf of a company, business, or other legal entity, Customer represents that Customer has the authority to bind such entity
    type: business
  minimum_age:
    text: THIS WEBSITE, SUBSCRIPTION SERVICES, AND THE PRODUCT ARE OFFERED AND AVAILABLE TO USERS WHO ARE 18 YEARS OF AGE OR OLDER.
    value: '18'
  restricted_uses:
  - summary: Illegal or illicit product advertising
    text: advertise, sell, or exchange any products or services related to illegal or illicit activities, including, without limitation, payday loan services, sex products or services, drug products or services, pornographic materials, weapons, or involving credit repair services
  - summary: Restricted data uses (FCRA etc.)
    text: or use the Data in connection with credit granting, credit monitoring, account review, collections, insurance underwriting, employment or any other purpose covered by the Fair Credit Reporting Act
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
name: UpLead
provenance_date: '2026-11-10'
provider_name: UpLead
provider_slug: uplead
slug: uplead-eligibility
source_date: '2026-11-10'
source_filename: uplead-eligibility.yml
source_heading: Eligibility
source_page: https://www.uplead.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UpLead\naid: uplead\nurl: https://www.uplead.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: UpLead is based in the United States. We make no claims that the Subscription Services, Product, or the\n    Website or any of their content is accessible or appropriate outside of the United States.\nentity_types:\n- type: business\n  text: If Customer is entering into these License Terms on behalf of a company, business, or other legal entity,\n    Customer represents that Customer has the authority to bind such entity\nrestricted_uses:\n- summary: Illegal or illicit\
  \ product advertising\n  text: advertise, sell, or exchange any products or services related to illegal or illicit activities, including,\n    without limitation, payday loan services, sex products or services, drug products or services, pornographic\n    materials, weapons, or involving credit repair services\n- summary: Restricted data uses (FCRA etc.)\n  text: or use the Data in connection with credit granting, credit monitoring, account review, collections, insurance\n    underwriting, employment or any other purpose covered by the Fair Credit Reporting Act\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: THIS WEBSITE, SUBSCRIPTION SERVICES, AND THE PRODUCT ARE OFFERED AND AVAILABLE TO USERS WHO ARE 18 YEARS\n    OF AGE OR OLDER.\n"
source_yaml_url: https://artifacts.apis.io/uplead/eligibility/uplead-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from UpLead's own page on 2026-11-10.
synthetic: false
tags:
- B2B
- Lead Generation
- Contact Data
- Company Data
- Email Verification
- Data Enrichment
- Sales Intelligence
---
