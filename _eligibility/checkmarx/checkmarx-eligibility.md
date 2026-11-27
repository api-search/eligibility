---
api_specs:
- filename: checkmarx-applications-api-openapi.yml
  format: yaml
  label: Checkmarx Applications API
  slug: checkmarx-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-applications-api-openapi.yml
- filename: checkmarx-authentication-api-openapi.yml
  format: yaml
  label: Checkmarx Authentication API
  slug: checkmarx-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-authentication-api-openapi.yml
- filename: checkmarx-configuration-api-openapi.yml
  format: yaml
  label: Checkmarx Configuration API
  slug: checkmarx-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-configuration-api-openapi.yml
- filename: checkmarx-engines-api-openapi.yml
  format: yaml
  label: Checkmarx Engines API
  slug: checkmarx-engines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-engines-api-openapi.yml
- filename: checkmarx-groups-api-openapi.yml
  format: yaml
  label: Checkmarx Groups API
  slug: checkmarx-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-groups-api-openapi.yml
- filename: checkmarx-packages-api-openapi.yml
  format: yaml
  label: Checkmarx Packages API
  slug: checkmarx-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-packages-api-openapi.yml
- filename: checkmarx-presets-api-openapi.yml
  format: yaml
  label: Checkmarx Presets API
  slug: checkmarx-presets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-presets-api-openapi.yml
- filename: checkmarx-projects-api-openapi.yml
  format: yaml
  label: Checkmarx Projects API
  slug: checkmarx-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-projects-api-openapi.yml
- filename: checkmarx-queries-api-openapi.yml
  format: yaml
  label: Checkmarx Queries API
  slug: checkmarx-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-queries-api-openapi.yml
- filename: checkmarx-reports-api-openapi.yml
  format: yaml
  label: Checkmarx Reports API
  slug: checkmarx-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-reports-api-openapi.yml
- filename: checkmarx-results-api-openapi.yml
  format: yaml
  label: Checkmarx Results API
  slug: checkmarx-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-results-api-openapi.yml
- filename: checkmarx-risk-reports-api-openapi.yml
  format: yaml
  label: Checkmarx Risk Reports API
  slug: checkmarx-risk-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-risk-reports-api-openapi.yml
- filename: checkmarx-scans-api-openapi.yml
  format: yaml
  label: Checkmarx Scans API
  slug: checkmarx-scans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-scans-api-openapi.yml
- filename: checkmarx-settings-api-openapi.yml
  format: yaml
  label: Checkmarx Settings API
  slug: checkmarx-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-settings-api-openapi.yml
- filename: checkmarx-teams-api-openapi.yml
  format: yaml
  label: Checkmarx Teams API
  slug: checkmarx-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmarx/openapi/checkmarx-teams-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Users must not be barred from using the Site under the laws of the United States or other countries including the country in which they are domiciled.
  entity_types:
  - text: This site is aimed for use by individuals who are natural persons who are of sufficient legal age and capability to form a binding agreement under the laws of their domicile.
    type: individual
  minimum_age:
    text: you are not of legal age to form a binding contract with Checkmarx (as determined in your domicile)
    value: null
  restricted_uses:
  - summary: Commercial purposes prohibited
    text: Any use of the Site or any parts thereof or information therein for any commercial purposes is prohibited.
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
name: Checkmarx
provenance_date: '2026-11-09'
provider_name: Checkmarx
provider_slug: checkmarx
slug: checkmarx-eligibility
source_date: '2026-11-09'
source_filename: checkmarx-eligibility.yml
source_heading: Eligibility
source_page: https://checkmarx.com/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Checkmarx\naid: checkmarx\nurl: https://checkmarx.com/legal/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Users must not be barred from using the Site under the laws of the United States or other countries including\n    the country in which they are domiciled.\nentity_types:\n- type: individual\n  text: This site is aimed for use by individuals who are natural persons who are of sufficient legal age and capability\n    to form a binding agreement under the laws of their domicile.\nrestricted_uses:\n- summary: Commercial purposes prohibited\n  text: Any use of the\
  \ Site or any parts thereof or information therein for any commercial purposes is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are not of legal age to form a binding contract with Checkmarx (as determined in your domicile)\n"
source_yaml_url: https://artifacts.apis.io/checkmarx/eligibility/checkmarx-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Checkmarx's own page on 2026-11-09.
synthetic: false
tags:
- Application Security
- Code Analysis
- DevSecOps
- SAST
- Security Testing
- Vulnerability Scanning
---
