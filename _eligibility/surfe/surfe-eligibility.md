---
api_specs:
- filename: surfe-account-api-openapi.yml
  format: yaml
  label: Surfe Account API
  slug: surfe-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfe/openapi/surfe-account-api-openapi.yml
- filename: surfe-companies-api-openapi.yml
  format: yaml
  label: Surfe Companies API
  slug: surfe-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfe/openapi/surfe-companies-api-openapi.yml
- filename: surfe-people-api-openapi.yml
  format: yaml
  label: Surfe People API
  slug: surfe-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfe/openapi/surfe-people-api-openapi.yml
- filename: surfe-recommendations-api-openapi.yml
  format: yaml
  label: Surfe Recommendations API
  slug: surfe-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfe/openapi/surfe-recommendations-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are intended only for Commercial use purposes, whether Customer is acting in the name of or on behalf of another entity.
    type: business
  - text: 'Purchase of Credits, access to and use of the API and Services is specifically limited to: NATURAL PERSONS with full legal capacity, power, and authority to be bound by the Terms and Conditions'
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No personal, family or household use
    text: If you intend to use our Services for personal, family, or household purposes, then you are ineligible to sign-in.
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
name: Surfe
provenance_date: '2026-11-10'
provider_name: Surfe
provider_slug: surfe
slug: surfe-eligibility
source_date: '2026-11-10'
source_filename: surfe-eligibility.yml
source_heading: Eligibility
source_page: https://www.surfe.com/terms-and-conditions-api
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Surfe\naid: surfe\nurl: https://www.surfe.com/terms-and-conditions-api\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are intended only for Commercial use purposes, whether Customer is acting in the name of or\n    on behalf of another entity.\n- type: individual\n  text: 'Purchase of Credits, access to and use of the API and Services is specifically limited to: NATURAL PERSONS\n    with full legal capacity, power, and authority to be bound by the Terms and Conditions'\nrestricted_uses:\n- summary: No personal, family or\
  \ household use\n  text: If you intend to use our Services for personal, family, or household purposes, then you are ineligible to\n    sign-in.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/surfe/eligibility/surfe-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Surfe's own page on 2026-11-10.
synthetic: false
tags:
- B2B Data
- Contact Data
- Sales Intelligence
- Data Enrichment
- Lead Generation
- CRM
- Prospecting
---
