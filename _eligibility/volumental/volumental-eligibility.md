---
api_specs:
- filename: volumental-auth-api-openapi.yml
  format: yaml
  label: Volumental Auth API
  slug: volumental-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volumental/openapi/volumental-auth-api-openapi.yml
- filename: volumental-oauth-api-openapi.yml
  format: yaml
  label: Volumental OAuth API
  slug: volumental-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volumental/openapi/volumental-oauth-api-openapi.yml
- filename: volumental-recommendations-api-openapi.yml
  format: yaml
  label: Volumental Recommendations API
  slug: volumental-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volumental/openapi/volumental-recommendations-api-openapi.yml
- filename: volumental-scans-api-openapi.yml
  format: yaml
  label: Volumental Scans API
  slug: volumental-scans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volumental/openapi/volumental-scans-api-openapi.yml
- filename: volumental-some-endpoint-api-openapi.yml
  format: yaml
  label: Volumental Some Endpoint API
  slug: volumental-some-endpoint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volumental/openapi/volumental-some-endpoint-api-openapi.yml
- filename: volumental-v1alpha-api-openapi.yml
  format: yaml
  label: Volumental V1Alpha API
  slug: volumental-v1alpha-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volumental/openapi/volumental-v1alpha-api-openapi.yml
- filename: volumental-v1beta-api-openapi.yml
  format: yaml
  label: Volumental V1Beta API
  slug: volumental-v1beta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volumental/openapi/volumental-v1beta-api-openapi.yml
- filename: volumental-volumental-api-api-openapi.yml
  format: yaml
  label: Volumental Volumental API
  slug: volumental-volumental-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volumental/openapi/volumental-volumental-api-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: If you are under 16, you may only use the Service with the prior consent of your parent or legal guardian.
    value: '16'
  restricted_uses:
  - summary: Only intended purpose
    text: We do not want the Service to be used for anything other than its intended purpose
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
name: Volumental
provenance_date: '2026-11-10'
provider_name: Volumental
provider_slug: volumental
slug: volumental-eligibility
source_date: '2026-11-10'
source_filename: volumental-eligibility.yml
source_heading: Eligibility
source_page: https://volumental.com/policy/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Volumental\naid: volumental\nurl: https://volumental.com/policy/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Only intended purpose\n  text: We do not want the Service to be used for anything other than its intended purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: If you are under 16, you may only use the Service with the prior consent of your parent or legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/volumental/eligibility/volumental-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Volumental's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Retail
- Footwear
- 3D Scanning
- Artificial Intelligence
---
