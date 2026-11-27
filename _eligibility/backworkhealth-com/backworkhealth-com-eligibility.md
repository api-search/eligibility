---
api_specs:
- filename: backworkhealth-com-agent-tools-api-openapi.yml
  format: yaml
  label: Backwork Agent Tools API
  slug: backworkhealth-com-agent-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backworkhealth-com/openapi/backworkhealth-com-agent-tools-api-openapi.yml
- filename: backworkhealth-com-certified-releases-api-openapi.yml
  format: yaml
  label: Backwork Certified Releases API
  slug: backworkhealth-com-certified-releases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backworkhealth-com/openapi/backworkhealth-com-certified-releases-api-openapi.yml
- filename: backworkhealth-com-claims-api-openapi.yml
  format: yaml
  label: Backwork Claims API
  slug: backworkhealth-com-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backworkhealth-com/openapi/backworkhealth-com-claims-api-openapi.yml
- filename: backworkhealth-com-codes-api-openapi.yml
  format: yaml
  label: Backwork Codes API
  slug: backworkhealth-com-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backworkhealth-com/openapi/backworkhealth-com-codes-api-openapi.yml
- filename: backworkhealth-com-compliance-api-openapi.yml
  format: yaml
  label: Backwork Compliance API
  slug: backworkhealth-com-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backworkhealth-com/openapi/backworkhealth-com-compliance-api-openapi.yml
- filename: backworkhealth-com-coverage-api-openapi.yml
  format: yaml
  label: Backwork Coverage API
  slug: backworkhealth-com-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backworkhealth-com/openapi/backworkhealth-com-coverage-api-openapi.yml
- filename: backworkhealth-com-drugs-api-openapi.yml
  format: yaml
  label: Backwork Drugs API
  slug: backworkhealth-com-drugs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backworkhealth-com/openapi/backworkhealth-com-drugs-api-openapi.yml
- filename: backworkhealth-com-health-api-openapi.yml
  format: yaml
  label: Backwork Health API
  slug: backworkhealth-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backworkhealth-com/openapi/backworkhealth-com-health-api-openapi.yml
- filename: backworkhealth-com-policies-api-openapi.yml
  format: yaml
  label: Backwork Policies API
  slug: backworkhealth-com-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backworkhealth-com/openapi/backworkhealth-com-policies-api-openapi.yml
- filename: backworkhealth-com-prior-auth-api-openapi.yml
  format: yaml
  label: Backwork Prior Auth API
  slug: backworkhealth-com-prior-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backworkhealth-com/openapi/backworkhealth-com-prior-auth-api-openapi.yml
- filename: backworkhealth-com-reference-api-openapi.yml
  format: yaml
  label: Backwork Reference API
  slug: backworkhealth-com-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backworkhealth-com/openapi/backworkhealth-com-reference-api-openapi.yml
- filename: backworkhealth-com-spending-api-openapi.yml
  format: yaml
  label: Backwork Spending API
  slug: backworkhealth-com-spending-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backworkhealth-com/openapi/backworkhealth-com-spending-api-openapi.yml
- filename: backworkhealth-com-webhooks-api-openapi.yml
  format: yaml
  label: Backwork Webhooks API
  slug: backworkhealth-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backworkhealth-com/openapi/backworkhealth-com-webhooks-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Protected health information
    text: Submit patient names, dates of birth, member IDs, medical record numbers, claim IDs, chart notes, or other PHI/ePHI unless we have explicitly entered a PHI-enabled agreement with you
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
name: Backwork
provenance_date: '2026-11-09'
provider_name: Backwork
provider_slug: backworkhealth-com
slug: backworkhealth-com-eligibility
source_date: '2026-11-09'
source_filename: backworkhealth-com-eligibility.yml
source_heading: Eligibility
source_page: https://backworkhealth.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Backwork\naid: backworkhealth-com\nurl: https://backworkhealth.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Protected health information\n  text: Submit patient names, dates of birth, member IDs, medical record numbers, claim IDs, chart notes, or other\n    PHI/ePHI unless we have explicitly entered a PHI-enabled agreement with you\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/backworkhealth-com/eligibility/backworkhealth-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Backwork's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Insurance
- Policy
- Medicare
- Compliance
---
