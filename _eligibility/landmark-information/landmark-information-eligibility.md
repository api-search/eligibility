---
api_specs:
- filename: landmark-information-activities-api-openapi.yml
  format: yaml
  label: Landmark Information Group Activities API
  slug: landmark-information-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landmark-information/openapi/landmark-information-activities-api-openapi.yml
- filename: landmark-information-cases-api-openapi.yml
  format: yaml
  label: Landmark Information Group Cases API
  slug: landmark-information-cases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landmark-information/openapi/landmark-information-cases-api-openapi.yml
- filename: landmark-information-document-vaults-api-openapi.yml
  format: yaml
  label: Landmark Information Group Document Vaults API
  slug: landmark-information-document-vaults-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landmark-information/openapi/landmark-information-document-vaults-api-openapi.yml
- filename: landmark-information-documents-api-openapi.yml
  format: yaml
  label: Landmark Information Group Documents API
  slug: landmark-information-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landmark-information/openapi/landmark-information-documents-api-openapi.yml
- filename: landmark-information-milestones-api-openapi.yml
  format: yaml
  label: Landmark Information Group Milestones API
  slug: landmark-information-milestones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landmark-information/openapi/landmark-information-milestones-api-openapi.yml
- filename: landmark-information-order-experience-api-api-openapi.yml
  format: yaml
  label: Landmark Information Group Order Experience API
  slug: landmark-information-order-experience-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landmark-information/openapi/landmark-information-order-experience-api-api-openapi.yml
- filename: landmark-information-quotes-api-openapi.yml
  format: yaml
  label: Landmark Information Group Quotes API
  slug: landmark-information-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landmark-information/openapi/landmark-information-quotes-api-openapi.yml
- filename: landmark-information-transaction-requests-api-openapi.yml
  format: yaml
  label: Landmark Information Group Transaction Requests API
  slug: landmark-information-transaction-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landmark-information/openapi/landmark-information-transaction-requests-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: Our site is directed to people residing in the United Kingdom.
  entity_types:
  - text: 'If you are a business user: We exclude all implied conditions, warranties, representations or other terms that may apply to our site'
    type: business
  - text: If you are a consumer, please note that these terms of use, their subject matter and their formation, are governed by English law.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial use by consumers
    text: You agree not to use our site for any commercial or business purposes
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You will be required to register your details and/or open an account to access the client portal via our site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Landmark Information Group
provenance_date: '2026-11-09'
provider_name: Landmark Information Group
provider_slug: landmark-information
slug: landmark-information-eligibility
source_date: '2026-11-09'
source_filename: landmark-information-eligibility.yml
source_heading: Eligibility
source_page: https://www.landmark.co.uk/website-terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Landmark Information Group\naid: landmark-information\nurl: https://www.landmark.co.uk/website-terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: Our site is directed to people residing in the United Kingdom.\nentity_types:\n- type: business\n  text: 'If you are a business user: We exclude all implied conditions, warranties, representations or other terms\n    that may apply to our site'\n- type: individual\n  text: If you are a consumer, please note that these terms of use, their subject matter and their formation, are\n    governed by English law.\nrestricted_uses:\n\
  - summary: No commercial use by consumers\n  text: You agree not to use our site for any commercial or business purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You will be required to register your details and/or open an account to access the client portal via our\n    site.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/landmark-information/eligibility/landmark-information-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Landmark Information Group's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- United Kingdom
- PropTech
- Property Data
- Conveyancing
- Land Registry
- Geospatial
- Valuation
- AML
- Planning Data
- Mortgage
---
