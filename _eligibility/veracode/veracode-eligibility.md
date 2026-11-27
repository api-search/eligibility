---
api_specs:
- filename: veracode-api-credentials-api-openapi.yml
  format: yaml
  label: Veracode API Credentials API
  slug: veracode-api-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veracode/openapi/veracode-api-credentials-api-openapi.yml
- filename: veracode-applications-api-openapi.yml
  format: yaml
  label: Veracode Applications API
  slug: veracode-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veracode/openapi/veracode-applications-api-openapi.yml
- filename: veracode-business-units-api-openapi.yml
  format: yaml
  label: Veracode Business Units API
  slug: veracode-business-units-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veracode/openapi/veracode-business-units-api-openapi.yml
- filename: veracode-findings-api-openapi.yml
  format: yaml
  label: Veracode Findings API
  slug: veracode-findings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veracode/openapi/veracode-findings-api-openapi.yml
- filename: veracode-manual-penetration-testing-api-openapi.yml
  format: yaml
  label: Veracode Manual Penetration Testing API
  slug: veracode-manual-penetration-testing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veracode/openapi/veracode-manual-penetration-testing-api-openapi.yml
- filename: veracode-policy-evaluations-api-openapi.yml
  format: yaml
  label: Veracode Policy Evaluations API
  slug: veracode-policy-evaluations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veracode/openapi/veracode-policy-evaluations-api-openapi.yml
- filename: veracode-reports-api-openapi.yml
  format: yaml
  label: Veracode Reports API
  slug: veracode-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veracode/openapi/veracode-reports-api-openapi.yml
- filename: veracode-roles-api-openapi.yml
  format: yaml
  label: Veracode Roles API
  slug: veracode-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veracode/openapi/veracode-roles-api-openapi.yml
- filename: veracode-sandboxes-api-openapi.yml
  format: yaml
  label: Veracode Sandboxes API
  slug: veracode-sandboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veracode/openapi/veracode-sandboxes-api-openapi.yml
- filename: veracode-teams-api-openapi.yml
  format: yaml
  label: Veracode Teams API
  slug: veracode-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veracode/openapi/veracode-teams-api-openapi.yml
- filename: veracode-users-api-openapi.yml
  format: yaml
  label: Veracode Users API
  slug: veracode-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veracode/openapi/veracode-users-api-openapi.yml
- filename: veracode-api-credentials-api-openapi.yml
  format: yaml
  label: Veracode API Credentials API
  slug: veracode-api-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veracode/openapi/veracode-api-credentials-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We may limit the availability of the Services, in whole or in part, to any person, geographic area or jurisdiction we choose
  entity_types:
  - text: if you access the Services on behalf of a corporation or other legal entity, you and such corporation or other legal entity on whose behalf you access the Services
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or fraudulent use
    text: Use a Service for any fraudulent or unlawful purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register with us in order to access certain Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Veracode
provenance_date: '2026-11-10'
provider_name: Veracode
provider_slug: veracode
slug: veracode-eligibility
source_date: '2026-11-10'
source_filename: veracode-eligibility.yml
source_heading: Eligibility
source_page: https://www.veracode.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Veracode\naid: veracode\nurl: https://www.veracode.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We may limit the availability of the Services, in whole or in part, to any person, geographic area or jurisdiction\n    we choose\nentity_types:\n- type: business\n  text: if you access the Services on behalf of a corporation or other legal entity, you and such corporation or\n    other legal entity on whose behalf you access the Services\nrestricted_uses:\n- summary: Unlawful or fraudulent use\n  text: Use a Service for any fraudulent or unlawful purpose.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register with us in order to access certain Services.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/veracode/eligibility/veracode-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Veracode's own page on 2026-11-10.
synthetic: false
tags:
- Application Security
- SAST
- DAST
- Software Composition Analysis
- Security Testing
- DevSecOps
---
