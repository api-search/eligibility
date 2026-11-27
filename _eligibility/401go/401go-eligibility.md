---
api_specs:
- filename: 401go-affiliates-firms-api-openapi.yml
  format: yaml
  label: 401GO Affiliates & Firms API
  slug: 401go-affiliates-firms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/401go/openapi/401go-affiliates-firms-api-openapi.yml
- filename: 401go-beneficiaries-api-openapi.yml
  format: yaml
  label: 401GO Beneficiaries API
  slug: 401go-beneficiaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/401go/openapi/401go-beneficiaries-api-openapi.yml
- filename: 401go-companies-plans-api-openapi.yml
  format: yaml
  label: 401GO Companies & Plans API
  slug: 401go-companies-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/401go/openapi/401go-companies-plans-api-openapi.yml
- filename: 401go-contributions-payroll-api-openapi.yml
  format: yaml
  label: 401GO Contributions & Payroll API
  slug: 401go-contributions-payroll-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/401go/openapi/401go-contributions-payroll-api-openapi.yml
- filename: 401go-documents-api-openapi.yml
  format: yaml
  label: 401GO Documents API
  slug: 401go-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/401go/openapi/401go-documents-api-openapi.yml
- filename: 401go-investments-portfolios-api-openapi.yml
  format: yaml
  label: 401GO Investments & Portfolios API
  slug: 401go-investments-portfolios-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/401go/openapi/401go-investments-portfolios-api-openapi.yml
- filename: 401go-money-movement-api-openapi.yml
  format: yaml
  label: 401GO Money Movement API
  slug: 401go-money-movement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/401go/openapi/401go-money-movement-api-openapi.yml
- filename: 401go-notifications-api-openapi.yml
  format: yaml
  label: 401GO Notifications API
  slug: 401go-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/401go/openapi/401go-notifications-api-openapi.yml
- filename: 401go-participants-api-openapi.yml
  format: yaml
  label: 401GO Participants API
  slug: 401go-participants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/401go/openapi/401go-participants-api-openapi.yml
- filename: 401go-retirement-planning-api-openapi.yml
  format: yaml
  label: 401GO Retirement Planning API
  slug: 401go-retirement-planning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/401go/openapi/401go-retirement-planning-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (i) You are not located in a country that is subject to the United States government embargo, or that has been designated by the United States government as a “terrorist supporting” country
  entity_types:
  - text: You means the individual accessing or using the Service
    type: individual
  - text: or the company, or other legal entity on behalf of which such individual is accessing or using the Service
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctions and restricted parties
    text: You are not listed on any United States government list of prohibited or restricted parties.
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
name: 401GO
provenance_date: '2026-11-09'
provider_name: 401GO
provider_slug: 401go
slug: 401go-eligibility
source_date: '2026-11-09'
source_filename: 401go-eligibility.yml
source_heading: Eligibility
source_page: https://401go.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 401GO\naid: 401go\nurl: https://401go.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (i) You are not located in a country that is subject to the United States\n    government embargo, or that has been designated by the United States government as a “terrorist supporting”\n    country\nentity_types:\n- type: individual\n  text: You means the individual accessing or using the Service\n- type: business\n  text: or the company, or other legal entity on behalf of which such individual is accessing or using the Service\nrestricted_uses:\n\
  - summary: Sanctions and restricted parties\n  text: You are not listed on any United States government list of prohibited or restricted parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/401go/eligibility/401go-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from 401GO's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Retirement
- 401k
- Financial Services
- Fintech
- Payroll
- Human Resources
- Benefits
- Investment
- Wealth Management
- Employee Benefits
---
