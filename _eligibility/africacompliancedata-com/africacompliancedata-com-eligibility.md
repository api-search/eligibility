---
api_specs:
- filename: africacompliancedata-com-countries-api-openapi.yml
  format: yaml
  label: africacompliancedata-com Countries API
  slug: africacompliancedata-com-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/africacompliancedata-com/openapi/africacompliancedata-com-countries-api-openapi.yml
- filename: africacompliancedata-com-holidays-and-business-days-api-openapi.yml
  format: yaml
  label: africacompliancedata-com Holidays and business days API
  slug: africacompliancedata-com-holidays-and-business-days-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/africacompliancedata-com/openapi/africacompliancedata-com-holidays-and-business-days-api-openapi.yml
- filename: africacompliancedata-com-private-mode-api-openapi.yml
  format: yaml
  label: africacompliancedata-com Private mode API
  slug: africacompliancedata-com-private-mode-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/africacompliancedata-com/openapi/africacompliancedata-com-private-mode-api-openapi.yml
- filename: africacompliancedata-com-public-api-openapi.yml
  format: yaml
  label: africacompliancedata-com Public API
  slug: africacompliancedata-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/africacompliancedata-com/openapi/africacompliancedata-com-public-api-openapi.yml
- filename: africacompliancedata-com-tax-data-api-openapi.yml
  format: yaml
  label: africacompliancedata-com Tax data API
  slug: africacompliancedata-com-tax-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/africacompliancedata-com/openapi/africacompliancedata-com-tax-data-api-openapi.yml
- filename: africacompliancedata-com-webhooks-api-openapi.yml
  format: yaml
  label: africacompliancedata-com Webhooks API
  slug: africacompliancedata-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/africacompliancedata-com/openapi/africacompliancedata-com-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Sanctions section: not on US, UN, EU or UK sanctions lists and not located in comprehensively sanctioned US countries or regions.'
  minimum_age:
    text: You must be at least 18.
    value: '18'
  restricted_uses:
  - summary: Free plan non-commercial only
    text: The Free plan is for testing, learning and personal, non-commercial use; commercial use needs a paid plan, except the public holiday calendar feeds below.
  - summary: Sanctions and unlawful use
    text: use the Service for anything unlawful, fraudulent or harmful, or in breach of sanctions (section 15).
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
name: africacompliancedata-com
provenance_date: '2026-11-09'
provider_name: africacompliancedata-com
provider_slug: africacompliancedata-com
slug: africacompliancedata-com-eligibility
source_date: '2026-11-09'
source_filename: africacompliancedata-com-eligibility.yml
source_heading: Eligibility
source_page: https://africacompliancedata.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: africacompliancedata-com\naid: africacompliancedata-com\nurl: https://africacompliancedata.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Sanctions section: not on US, UN, EU or UK sanctions lists and not located in comprehensively sanctioned\n    US countries or regions.'\nentity_types: []\nrestricted_uses:\n- summary: Free plan non-commercial only\n  text: The Free plan is for testing, learning and personal, non-commercial use; commercial use needs a paid plan,\n    except the public holiday calendar feeds below.\n- summary: Sanctions and unlawful use\n  text: use the\
  \ Service for anything unlawful, fraudulent or harmful, or in breach of sanctions (section 15).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18.\n"
source_yaml_url: https://artifacts.apis.io/africacompliancedata-com/eligibility/africacompliancedata-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from africacompliancedata-com's own page on 2026-11-09.
synthetic: false
tags:
- Africa
- Compliance
- Tax
- Holidays
- Data
---
