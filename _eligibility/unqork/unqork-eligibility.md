---
api_specs:
- filename: unqork-applications-api-openapi.yml
  format: yaml
  label: Unqork Applications API
  slug: unqork-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unqork/openapi/unqork-applications-api-openapi.yml
- filename: unqork-authentication-api-openapi.yml
  format: yaml
  label: Unqork Authentication API
  slug: unqork-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unqork/openapi/unqork-authentication-api-openapi.yml
- filename: unqork-credentials-api-openapi.yml
  format: yaml
  label: Unqork Credentials API
  slug: unqork-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unqork/openapi/unqork-credentials-api-openapi.yml
- filename: unqork-data-collections-api-openapi.yml
  format: yaml
  label: Unqork Data Collections API
  slug: unqork-data-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unqork/openapi/unqork-data-collections-api-openapi.yml
- filename: unqork-data-model-records-api-openapi.yml
  format: yaml
  label: Unqork Data Model Records API
  slug: unqork-data-model-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unqork/openapi/unqork-data-model-records-api-openapi.yml
- filename: unqork-global-variables-api-openapi.yml
  format: yaml
  label: Unqork Global Variables API
  slug: unqork-global-variables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unqork/openapi/unqork-global-variables-api-openapi.yml
- filename: unqork-groups-api-openapi.yml
  format: yaml
  label: Unqork Groups API
  slug: unqork-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unqork/openapi/unqork-groups-api-openapi.yml
- filename: unqork-logs-api-openapi.yml
  format: yaml
  label: Unqork Logs API
  slug: unqork-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unqork/openapi/unqork-logs-api-openapi.yml
- filename: unqork-modules-api-openapi.yml
  format: yaml
  label: Unqork Modules API
  slug: unqork-modules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unqork/openapi/unqork-modules-api-openapi.yml
- filename: unqork-promotions-api-openapi.yml
  format: yaml
  label: Unqork Promotions API
  slug: unqork-promotions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unqork/openapi/unqork-promotions-api-openapi.yml
- filename: unqork-query-api-openapi.yml
  format: yaml
  label: Unqork Query API
  slug: unqork-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unqork/openapi/unqork-query-api-openapi.yml
- filename: unqork-revisions-api-openapi.yml
  format: yaml
  label: Unqork Revisions API
  slug: unqork-revisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unqork/openapi/unqork-revisions-api-openapi.yml
- filename: unqork-search-configs-api-openapi.yml
  format: yaml
  label: Unqork Search Configs API
  slug: unqork-search-configs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unqork/openapi/unqork-search-configs-api-openapi.yml
- filename: unqork-submissions-api-openapi.yml
  format: yaml
  label: Unqork Submissions API
  slug: unqork-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unqork/openapi/unqork-submissions-api-openapi.yml
- filename: unqork-transforms-api-openapi.yml
  format: yaml
  label: Unqork Transforms API
  slug: unqork-transforms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unqork/openapi/unqork-transforms-api-openapi.yml
- filename: unqork-users-api-openapi.yml
  format: yaml
  label: Unqork Users API
  slug: unqork-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unqork/openapi/unqork-users-api-openapi.yml
- filename: unqork-workflow-api-openapi.yml
  format: yaml
  label: Unqork Workflow API
  slug: unqork-workflow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unqork/openapi/unqork-workflow-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “ Customer ” means the entity that has entered into the Order and which is granted access and use of the services.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Discriminatory, harmful or unethical use
    text: use the Unqork Materials and/or Customer Data for purposes or with effects that are discriminatory, harassing, harmful, or unethical
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
name: Unqork
provenance_date: '2026-11-10'
provider_name: Unqork
provider_slug: unqork
slug: unqork-eligibility
source_date: '2026-11-10'
source_filename: unqork-eligibility.yml
source_heading: Eligibility
source_page: https://unqork.com/unqork-terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Unqork\naid: unqork\nurl: https://unqork.com/unqork-terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: “ Customer ” means the entity that has entered into the Order and which is granted access and use of the\n    services.\nrestricted_uses:\n- summary: Discriminatory, harmful or unethical use\n  text: use the Unqork Materials and/or Customer Data for purposes or with effects that are discriminatory, harassing,\n    harmful, or unethical\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/unqork/eligibility/unqork-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Unqork's own page on 2026-11-10.
synthetic: false
tags:
- Company
- No-Code
- Low-Code
- Application Development
- Enterprise Software
- Platform-as-a-Service
- Workflows
- Financial Services
- Insurance
- Government
- Application Modernization
---
