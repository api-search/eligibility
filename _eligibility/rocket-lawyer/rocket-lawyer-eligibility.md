---
api_specs:
- filename: rocket-lawyer-binders-api-openapi.yml
  format: yaml
  label: Rocket Lawyer Binders API
  slug: rocket-lawyer-binders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocket-lawyer/openapi/rocket-lawyer-binders-api-openapi.yml
- filename: rocket-lawyer-documents-api-openapi.yml
  format: yaml
  label: Rocket Lawyer Documents API
  slug: rocket-lawyer-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocket-lawyer/openapi/rocket-lawyer-documents-api-openapi.yml
- filename: rocket-lawyer-event-consumption-api-openapi.yml
  format: yaml
  label: Rocket Lawyer Event Consumption API
  slug: rocket-lawyer-event-consumption-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocket-lawyer/openapi/rocket-lawyer-event-consumption-api-openapi.yml
- filename: rocket-lawyer-interviews-api-openapi.yml
  format: yaml
  label: Rocket Lawyer Interviews API
  slug: rocket-lawyer-interviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocket-lawyer/openapi/rocket-lawyer-interviews-api-openapi.yml
- filename: rocket-lawyer-servicetoken-api-openapi.yml
  format: yaml
  label: Rocket Lawyer Servicetoken API
  slug: rocket-lawyer-servicetoken-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocket-lawyer/openapi/rocket-lawyer-servicetoken-api-openapi.yml
- filename: rocket-lawyer-subscription-management-api-openapi.yml
  format: yaml
  label: Rocket Lawyer Subscription Management API
  slug: rocket-lawyer-subscription-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocket-lawyer/openapi/rocket-lawyer-subscription-management-api-openapi.yml
- filename: rocket-lawyer-templates-api-openapi.yml
  format: yaml
  label: Rocket Lawyer Templates API
  slug: rocket-lawyer-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocket-lawyer/openapi/rocket-lawyer-templates-api-openapi.yml
- filename: rocket-lawyer-access-token-api-openapi.yml
  format: yaml
  label: Rocket Lawyer Access Token API
  slug: rocket-lawyer-access-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rocket-lawyer/openapi/rocket-lawyer-access-token-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are accepting this Agreement on behalf of a company or other legal entity, You represent that You have the authority to bind such entity.
    type: business
  minimum_age:
    text: You meet the requirements for the legal age of majority in the jurisdiction where You reside.
    value: age of majority
  restricted_uses:
  - summary: No ads tied to Service Data
    text: Applications shall not, in any manner, display any form of advertising to any user if such advertising is based on or connected to any Service Data.
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
name: Rocket Lawyer
provenance_date: '2026-11-10'
provider_name: Rocket Lawyer
provider_slug: rocket-lawyer
slug: rocket-lawyer-eligibility
source_date: '2026-11-10'
source_filename: rocket-lawyer-eligibility.yml
source_heading: Eligibility
source_page: https://www.rocketlawyer.com/developer-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rocket Lawyer\naid: rocket-lawyer\nurl: https://www.rocketlawyer.com/developer-terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If You are accepting this Agreement on behalf of a company or other legal entity, You represent that You\n    have the authority to bind such entity.\nrestricted_uses:\n- summary: No ads tied to Service Data\n  text: Applications shall not, in any manner, display any form of advertising to any user if such advertising is\n    based on or connected to any Service Data.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: You meet the requirements for the legal age of majority in the jurisdiction where You reside.\n"
source_yaml_url: https://artifacts.apis.io/rocket-lawyer/eligibility/rocket-lawyer-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Rocket Lawyer's own page on 2026-11-10.
synthetic: false
tags:
- Legal
- Legal Tech
- Legal Documents
- E-Signature
- Document Creation
- Document Management
- Business Formation
- LLC Formation
- Registered Agent
- Trademarks
- Wills
- Estate Planning
- Attorney Network
- Small Business
- Membership
- Embedded UX
- Partner API
- Apigee
- OpenAPI
---
