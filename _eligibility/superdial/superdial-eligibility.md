---
api_specs:
- filename: superdial-authentication-api-openapi.yml
  format: yaml
  label: SuperDial Authentication API
  slug: superdial-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superdial/openapi/superdial-authentication-api-openapi.yml
- filename: superdial-requests-api-openapi.yml
  format: yaml
  label: SuperDial Requests API
  slug: superdial-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superdial/openapi/superdial-requests-api-openapi.yml
- filename: superdial-schemas-api-openapi.yml
  format: yaml
  label: SuperDial Schemas API
  slug: superdial-schemas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superdial/openapi/superdial-schemas-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide the Products and Services for use only by persons and entities located within the United States.
  entity_types:
  - text: If you are an entity, the license granted in this Section 3 allows use of the Products and Services by only those of your employees, consultants, and agents who are authorized by you
    type: business
  - text: If you are an individual using the Products and Services for non-commercial purposes
    type: individual
  minimum_age:
    text: Any access to or use of the Products and Services by anyone under 18 years of age is strictly prohibited and in violation of these Terms.
    value: '18'
  restricted_uses:
  - summary: Fraudulent insurance claims
    text: to facilitate or conduct any fraud or misrepresentation, including any fraudulent insurance claims
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
name: SuperDial
provenance_date: '2026-11-10'
provider_name: SuperDial
provider_slug: superdial
slug: superdial-eligibility
source_date: '2026-11-10'
source_filename: superdial-eligibility.yml
source_heading: Eligibility
source_page: https://www.superdial.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SuperDial\naid: superdial\nurl: https://www.superdial.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide the Products and Services for use only by persons and entities located within the United States.\nentity_types:\n- type: business\n  text: If you are an entity, the license granted in this Section 3 allows use of the Products and Services by only\n    those of your employees, consultants, and agents who are authorized by you\n- type: individual\n  text: If you are an individual using the Products and Services for non-commercial purposes\nrestricted_uses:\n\
  - summary: Fraudulent insurance claims\n  text: to facilitate or conduct any fraud or misrepresentation, including any fraudulent insurance claims\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Any access to or use of the Products and Services by anyone under 18 years of age is strictly prohibited\n    and in violation of these Terms.\n"
source_yaml_url: https://artifacts.apis.io/superdial/eligibility/superdial-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from SuperDial's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Revenue Cycle Management
- Voice AI
- Insurance
- Artificial Intelligence
- Claims
- Prior Authorization
- Benefits Verification
- Automation
- A2A
---
