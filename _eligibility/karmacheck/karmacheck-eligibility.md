---
api_specs:
- filename: karmacheck-authentication-api-openapi.yml
  format: yaml
  label: KarmaCheck Authentication API
  slug: karmacheck-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karmacheck/openapi/karmacheck-authentication-api-openapi.yml
- filename: karmacheck-candidate-onboarding-api-openapi.yml
  format: yaml
  label: KarmaCheck Candidate onboarding API
  slug: karmacheck-candidate-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karmacheck/openapi/karmacheck-candidate-onboarding-api-openapi.yml
- filename: karmacheck-case-api-openapi.yml
  format: yaml
  label: KarmaCheck Case API
  slug: karmacheck-case-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karmacheck/openapi/karmacheck-case-api-openapi.yml
- filename: karmacheck-cases-api-openapi.yml
  format: yaml
  label: KarmaCheck Cases API
  slug: karmacheck-cases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karmacheck/openapi/karmacheck-cases-api-openapi.yml
- filename: karmacheck-packages-api-openapi.yml
  format: yaml
  label: KarmaCheck Packages API
  slug: karmacheck-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karmacheck/openapi/karmacheck-packages-api-openapi.yml
- filename: karmacheck-secure-documents-api-openapi.yml
  format: yaml
  label: KarmaCheck Secure documents API
  slug: karmacheck-secure-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karmacheck/openapi/karmacheck-secure-documents-api-openapi.yml
- filename: karmacheck-services-api-openapi.yml
  format: yaml
  label: KarmaCheck Services API
  slug: karmacheck-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karmacheck/openapi/karmacheck-services-api-openapi.yml
- filename: karmacheck-users-api-openapi.yml
  format: yaml
  label: KarmaCheck Users API
  slug: karmacheck-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karmacheck/openapi/karmacheck-users-api-openapi.yml
- filename: karmacheck-verification-book-api-openapi.yml
  format: yaml
  label: KarmaCheck Verification Book API
  slug: karmacheck-verification-book-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karmacheck/openapi/karmacheck-verification-book-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Website for use only by persons located in the United States.
  entity_types:
  - text: This Website is offered and available to users who are 18 years of age or older, of legal competence to enter into this agreement
    type: individual
  minimum_age:
    text: This Website is offered and available to users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Website only for lawful purposes and in accordance with these Terms of Service.
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
name: KarmaCheck
provenance_date: '2026-11-09'
provider_name: KarmaCheck
provider_slug: karmacheck
slug: karmacheck-eligibility
source_date: '2026-11-09'
source_filename: karmacheck-eligibility.yml
source_heading: Eligibility
source_page: https://www.karmacheck.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: KarmaCheck\naid: karmacheck\nurl: https://www.karmacheck.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Website for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: This Website is offered and available to users who are 18 years of age or older, of legal competence to\n    enter into this agreement\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Website only for lawful purposes and in accordance with these Terms of Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Website is offered and available to users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/karmacheck/eligibility/karmacheck-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from KarmaCheck's own page on 2026-11-09.
synthetic: false
tags:
- Background Checks
- Employment Screening
- Identity Verification
- Credential Verification
- Motor Vehicle Records
- Occupational Health Screening
- Drug Screening
- Human Resources
- Staffing
- Healthcare
- Compliance
- FCRA
- Adjudication
- Webhook
- MCP Server
- Agent-Native
---
