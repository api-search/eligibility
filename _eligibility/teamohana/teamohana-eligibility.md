---
api_specs:
- filename: teamohana-discovery-api-openapi.yml
  format: yaml
  label: TeamOhana Discovery API
  slug: teamohana-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamohana/openapi/teamohana-discovery-api-openapi.yml
- filename: teamohana-headcount-api-openapi.yml
  format: yaml
  label: TeamOhana Headcount API
  slug: teamohana-headcount-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamohana/openapi/teamohana-headcount-api-openapi.yml
- filename: teamohana-scenario-api-openapi.yml
  format: yaml
  label: TeamOhana Scenario API
  slug: teamohana-scenario-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamohana/openapi/teamohana-scenario-api-openapi.yml
- filename: teamohana-scim-api-openapi.yml
  format: yaml
  label: TeamOhana SCIM API
  slug: teamohana-scim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamohana/openapi/teamohana-scim-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Site is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to register for the Site.
    value: '18'
  restricted_uses:
  - summary: Prohibited activities
    text: Use the Site to advertise or offer to sell goods and services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register with the Site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: TeamOhana
provenance_date: '2026-11-10'
provider_name: TeamOhana
provider_slug: teamohana
slug: teamohana-eligibility
source_date: '2026-11-10'
source_filename: teamohana-eligibility.yml
source_heading: Eligibility
source_page: https://www.teamohana.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TeamOhana\naid: teamohana\nurl: https://www.teamohana.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited activities\n  text: Use the Site to advertise or offer to sell goods and services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register with the Site.\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to register for the Site.\n"
source_yaml_url: https://artifacts.apis.io/teamohana/eligibility/teamohana-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from TeamOhana's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Human Resources
- Headcount Management
- Headcount Planning
- Workforce Planning
- Talent Acquisition
- Finance
- SCIM
- Software-as-a-Service
---
