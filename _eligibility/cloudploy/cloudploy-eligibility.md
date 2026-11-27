---
api_specs:
- filename: cloudploy-apps-api-openapi.yml
  format: yaml
  label: CloudPloy Apps API
  slug: cloudploy-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudploy/openapi/cloudploy-apps-api-openapi.yml
- filename: cloudploy-deployments-api-openapi.yml
  format: yaml
  label: CloudPloy Deployments API
  slug: cloudploy-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudploy/openapi/cloudploy-deployments-api-openapi.yml
- filename: cloudploy-rollback-api-openapi.yml
  format: yaml
  label: CloudPloy Rollback API
  slug: cloudploy-rollback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudploy/openapi/cloudploy-rollback-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Ensure you are at least 18 years old or have parental/guardian consent
    value: '18'
  restricted_uses:
  - summary: Adult content
    text: Adult content, hate speech, or discriminatory material
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
name: CloudPloy
provenance_date: '2026-11-09'
provider_name: CloudPloy
provider_slug: cloudploy
slug: cloudploy-eligibility
source_date: '2026-11-09'
source_filename: cloudploy-eligibility.yml
source_heading: Eligibility
source_page: https://cloudploy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CloudPloy\naid: cloudploy\nurl: https://cloudploy.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Adult content\n  text: Adult content, hate speech, or discriminatory material\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Ensure you are at least 18 years old or have parental/guardian consent\n"
source_yaml_url: https://artifacts.apis.io/cloudploy/eligibility/cloudploy-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from CloudPloy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Deployment
- Artificial Intelligence
- Cloud
- Automation
---
