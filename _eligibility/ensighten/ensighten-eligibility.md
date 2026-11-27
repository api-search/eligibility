---
api_specs:
- filename: ensighten-authentication-api-openapi.yml
  format: yaml
  label: Ensighten Authentication API
  slug: ensighten-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-authentication-api-openapi.yml
- filename: ensighten-conditions-api-openapi.yml
  format: yaml
  label: Ensighten Conditions API
  slug: ensighten-conditions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-conditions-api-openapi.yml
- filename: ensighten-data-definitions-api-openapi.yml
  format: yaml
  label: Ensighten Data Definitions API
  slug: ensighten-data-definitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-data-definitions-api-openapi.yml
- filename: ensighten-deployments-api-openapi.yml
  format: yaml
  label: Ensighten Deployments API
  slug: ensighten-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-deployments-api-openapi.yml
- filename: ensighten-event-definitions-api-openapi.yml
  format: yaml
  label: Ensighten Event Definitions API
  slug: ensighten-event-definitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-event-definitions-api-openapi.yml
- filename: ensighten-git-api-openapi.yml
  format: yaml
  label: Ensighten GIT API
  slug: ensighten-git-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-git-api-openapi.yml
- filename: ensighten-labels-api-openapi.yml
  format: yaml
  label: Ensighten Labels API
  slug: ensighten-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-labels-api-openapi.yml
- filename: ensighten-publish-paths-api-openapi.yml
  format: yaml
  label: Ensighten Publish Paths API
  slug: ensighten-publish-paths-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-publish-paths-api-openapi.yml
- filename: ensighten-roles-api-openapi.yml
  format: yaml
  label: Ensighten Roles API
  slug: ensighten-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-roles-api-openapi.yml
- filename: ensighten-scim-2-0-api-openapi.yml
  format: yaml
  label: Ensighten SCIM 2.0 API
  slug: ensighten-scim-2-0-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-scim-2-0-api-openapi.yml
- filename: ensighten-spaces-api-openapi.yml
  format: yaml
  label: Ensighten Spaces API
  slug: ensighten-spaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-spaces-api-openapi.yml
- filename: ensighten-tdn-api-openapi.yml
  format: yaml
  label: Ensighten TDN API
  slug: ensighten-tdn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-tdn-api-openapi.yml
- filename: ensighten-users-api-openapi.yml
  format: yaml
  label: Ensighten Users API
  slug: ensighten-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ensighten/openapi/ensighten-users-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - IQ
    - LY
    - KP
    - SD
    - LB
    - SY
    served: []
    text: sell, distribute, export or download Services into (or to a national or resident of) Cuba, Iran, Iraq, Libya, North Korea, Sudan, Lebanon or Syria
  entity_types:
  - text: THE SERVICES ARE PROVIDED SOLELY FOR YOUR BUSINESS OWN USE.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or offensive activity
    text: use the Service for any activity that constitute, or encourages conduct that would constitute a criminal, offensive, give rise to civil liability or otherwise violate any applicable law
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- IQ
- LY
- KP
- SD
- LB
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ensighten
provenance_date: '2026-11-09'
provider_name: Ensighten
provider_slug: ensighten
slug: ensighten-eligibility
source_date: '2026-11-09'
source_filename: ensighten-eligibility.yml
source_heading: Eligibility
source_page: https://cheq.ai/cheq-terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ensighten\naid: ensighten\nurl: https://cheq.ai/cheq-terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - IQ\n  - LY\n  - KP\n  - SD\n  - LB\n  - SY\n  text: sell, distribute, export or download Services into (or to a national or resident of) Cuba, Iran, Iraq, Libya,\n    North Korea, Sudan, Lebanon or Syria\nentity_types:\n- type: business\n  text: THE SERVICES ARE PROVIDED SOLELY FOR YOUR BUSINESS OWN USE.\nrestricted_uses:\n- summary: Unlawful or offensive activity\n  text: use the Service for any activity that constitute, or encourages conduct that would\
  \ constitute a criminal,\n    offensive, give rise to civil liability or otherwise violate any applicable law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ensighten/eligibility/ensighten-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Ensighten's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Tag Management
- Data Governance
- Client-Side Security
- Consent Management
- Privacy Compliance
- Marketing Technology
---
