---
api_specs:
- filename: boltz-admin-api-openapi.yml
  format: yaml
  label: Boltz Admin API
  slug: boltz-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boltz/openapi/boltz-admin-api-openapi.yml
- filename: boltz-auth-api-openapi.yml
  format: yaml
  label: Boltz Auth API
  slug: boltz-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boltz/openapi/boltz-auth-api-openapi.yml
- filename: boltz-cli-api-openapi.yml
  format: yaml
  label: Boltz CLI API
  slug: boltz-cli-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boltz/openapi/boltz-cli-api-openapi.yml
- filename: boltz-predictions-api-openapi.yml
  format: yaml
  label: Boltz Predictions API
  slug: boltz-predictions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boltz/openapi/boltz-predictions-api-openapi.yml
- filename: boltz-protein-api-openapi.yml
  format: yaml
  label: Boltz Protein API
  slug: boltz-protein-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boltz/openapi/boltz-protein-api-openapi.yml
- filename: boltz-share-links-api-openapi.yml
  format: yaml
  label: Boltz Share Links API
  slug: boltz-share-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boltz/openapi/boltz-share-links-api-openapi.yml
- filename: boltz-small-molecule-api-openapi.yml
  format: yaml
  label: Boltz Small Molecule API
  slug: boltz-small-molecule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boltz/openapi/boltz-small-molecule-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents it is not located in, under the control of, or a national or resident of an Embargoed Country or Designated National.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: the Services may not be used, transferred, or otherwise exported or re-exported to countries as to which the United States, maintains an embargo
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
name: Boltz
provenance_date: '2026-11-09'
provider_name: Boltz
provider_slug: boltz
slug: boltz-eligibility
source_date: '2026-11-09'
source_filename: boltz-eligibility.yml
source_heading: Eligibility
source_page: https://docs.boltz.com/terms-of-service/terms-of-service.md
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Boltz\naid: boltz\nurl: https://docs.boltz.com/terms-of-service/terms-of-service.md\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents it is not located in, under the control of, or a national or resident of an Embargoed\n    Country or Designated National.\nentity_types: []\nrestricted_uses:\n- summary: Export restrictions\n  text: the Services may not be used, transferred, or otherwise exported or re-exported to countries as to which\n    the United States, maintains an embargo\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/boltz/eligibility/boltz-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Boltz's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Digital Biology
- Drug Discovery
- Artificial Intelligence
- Machine Learning
- Protein Design
- Structure Prediction
- Life Sciences
- Compute
---
