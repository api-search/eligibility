---
api_specs:
- filename: rollee-accounts-api-openapi.yml
  format: yaml
  label: Rollee Accounts API
  slug: rollee-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollee/openapi/rollee-accounts-api-openapi.yml
- filename: rollee-authentication-api-openapi.yml
  format: yaml
  label: Rollee Authentication API
  slug: rollee-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollee/openapi/rollee-authentication-api-openapi.yml
- filename: rollee-companies-api-openapi.yml
  format: yaml
  label: Rollee Companies API
  slug: rollee-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollee/openapi/rollee-companies-api-openapi.yml
- filename: rollee-company-accounts-api-openapi.yml
  format: yaml
  label: Rollee Company accounts API
  slug: rollee-company-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollee/openapi/rollee-company-accounts-api-openapi.yml
- filename: rollee-data-settings-api-openapi.yml
  format: yaml
  label: Rollee Data settings API
  slug: rollee-data-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollee/openapi/rollee-data-settings-api-openapi.yml
- filename: rollee-data-sources-api-openapi.yml
  format: yaml
  label: Rollee Data sources API
  slug: rollee-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollee/openapi/rollee-data-sources-api-openapi.yml
- filename: rollee-employer-endpoints-api-openapi.yml
  format: yaml
  label: Rollee Employer endpoints API
  slug: rollee-employer-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollee/openapi/rollee-employer-endpoints-api-openapi.yml
- filename: rollee-endpoints-api-openapi.yml
  format: yaml
  label: Rollee Endpoints API
  slug: rollee-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollee/openapi/rollee-endpoints-api-openapi.yml
- filename: rollee-fleet-endpoints-api-openapi.yml
  format: yaml
  label: Rollee Fleet endpoints API
  slug: rollee-fleet-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollee/openapi/rollee-fleet-endpoints-api-openapi.yml
- filename: rollee-sessions-api-openapi.yml
  format: yaml
  label: Rollee Sessions API
  slug: rollee-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollee/openapi/rollee-sessions-api-openapi.yml
- filename: rollee-users-api-openapi.yml
  format: yaml
  label: Rollee Users API
  slug: rollee-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollee/openapi/rollee-users-api-openapi.yml
- filename: rollee-webhooks-api-openapi.yml
  format: yaml
  label: Rollee Webhooks API
  slug: rollee-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollee/openapi/rollee-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Users domiciled or operating outside France are referenced, but no served or excluded countries are named.
  entity_types:
  - text: To any natural person with full legal capacity to enter into commitments under these Terms of Use.
    type: individual
  - text: To any legal entity acting through a natural person with the legal capacity to enter into contracts in the name and on behalf of the legal entity.
    type: business
  minimum_age:
    text: A natural person who does not have full legal capacity may only access the Application and the Services with the consent of their legal representative.
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
name: Rollee
provenance_date: '2026-11-10'
provider_name: Rollee
provider_slug: rollee
slug: rollee-eligibility
source_date: '2026-11-10'
source_filename: rollee-eligibility.yml
source_heading: Eligibility
source_page: https://www.getrollee.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rollee\naid: rollee\nurl: https://www.getrollee.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Users domiciled or operating outside France are referenced, but no served or excluded countries are named.\nentity_types:\n- type: individual\n  text: To any natural person with full legal capacity to enter into commitments under these Terms of Use.\n- type: business\n  text: To any legal entity acting through a natural person with the legal capacity to enter into contracts in the\n    name and on behalf of the legal entity.\nrestricted_uses: []\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: A natural person who does not have full legal capacity may only access the Application and the Services\n    with the consent of their legal representative.\n"
source_yaml_url: https://artifacts.apis.io/rollee/eligibility/rollee-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Rollee's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Open Finance
- Income Verification
- Employment Verification
- Payroll Data
- Gig Economy
- Alternative Data
- Underwriting
- Lending
- Fintech
---
