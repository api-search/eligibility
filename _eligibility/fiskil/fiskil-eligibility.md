---
api_specs:
- filename: fiskil-auth-api-openapi.yml
  format: yaml
  label: FISKIL Auth API
  slug: fiskil-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fiskil/openapi/fiskil-auth-api-openapi.yml
- filename: fiskil-banking-api-openapi.yml
  format: yaml
  label: FISKIL Banking API
  slug: fiskil-banking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fiskil/openapi/fiskil-banking-api-openapi.yml
- filename: fiskil-common-api-openapi.yml
  format: yaml
  label: FISKIL Common API
  slug: fiskil-common-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fiskil/openapi/fiskil-common-api-openapi.yml
- filename: fiskil-consent-api-openapi.yml
  format: yaml
  label: FISKIL Consent API
  slug: fiskil-consent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fiskil/openapi/fiskil-consent-api-openapi.yml
- filename: fiskil-end-users-api-openapi.yml
  format: yaml
  label: FISKIL End users API
  slug: fiskil-end-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fiskil/openapi/fiskil-end-users-api-openapi.yml
- filename: fiskil-energy-api-openapi.yml
  format: yaml
  label: FISKIL Energy API
  slug: fiskil-energy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fiskil/openapi/fiskil-energy-api-openapi.yml
- filename: fiskil-institutions-api-openapi.yml
  format: yaml
  label: FISKIL Institutions API
  slug: fiskil-institutions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fiskil/openapi/fiskil-institutions-api-openapi.yml
- filename: fiskil-transactions-api-openapi.yml
  format: yaml
  label: FISKIL Transactions API
  slug: fiskil-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fiskil/openapi/fiskil-transactions-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Terms apply solely to your use of Fiskil's services as a customer, including where you act as a representative of Fiskil under the Consumer Data Right (CDR).
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or unauthorized purposes
    text: Use the services for any unlawful or unauthorized purpose.
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
name: FISKIL
provenance_date: '2026-11-09'
provider_name: FISKIL
provider_slug: fiskil
slug: fiskil-eligibility
source_date: '2026-11-09'
source_filename: fiskil-eligibility.yml
source_heading: Eligibility
source_page: https://www.fiskil.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FISKIL\naid: fiskil\nurl: https://www.fiskil.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: These Terms apply solely to your use of Fiskil's services as a customer, including where you act as a representative\n    of Fiskil under the Consumer Data Right (CDR).\nrestricted_uses:\n- summary: Unlawful or unauthorized purposes\n  text: Use the services for any unlawful or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/fiskil/eligibility/fiskil-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from FISKIL's own page on 2026-11-09.
synthetic: false
tags:
- Open Banking
- Data Sharing
- Financial Services
- API Platform
- North America
---
