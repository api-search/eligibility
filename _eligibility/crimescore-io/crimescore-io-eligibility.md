---
api_specs:
- filename: crimescore-io-geocode-api-openapi.yml
  format: yaml
  label: crimescore-io Geocode API
  slug: crimescore-io-geocode-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crimescore-io/openapi/crimescore-io-geocode-api-openapi.yml
- filename: crimescore-io-incidents-api-openapi.yml
  format: yaml
  label: crimescore-io Incidents API
  slug: crimescore-io-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crimescore-io/openapi/crimescore-io-incidents-api-openapi.yml
- filename: crimescore-io-score-api-openapi.yml
  format: yaml
  label: crimescore-io Score API
  slug: crimescore-io-score-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crimescore-io/openapi/crimescore-io-score-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: CrimeScore provides location risk intelligence for US neighborhoods
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fair-housing and lending decisions
    text: Make individual-level decisions in fair-housing-protected contexts (rental approval, mortgage approval, lending decisions).
  - summary: Law-enforcement targeting
    text: Conduct predictive policing or any operational law-enforcement targeting.
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
name: crimescore-io
provenance_date: '2026-11-09'
provider_name: crimescore-io
provider_slug: crimescore-io
slug: crimescore-io-eligibility
source_date: '2026-11-09'
source_filename: crimescore-io-eligibility.yml
source_heading: Eligibility
source_page: https://crimescore.io/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: crimescore-io\naid: crimescore-io\nurl: https://crimescore.io/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: CrimeScore provides location risk intelligence for US neighborhoods\nentity_types: []\nrestricted_uses:\n- summary: Fair-housing and lending decisions\n  text: Make individual-level decisions in fair-housing-protected contexts (rental approval, mortgage approval,\n    lending decisions).\n- summary: Law-enforcement targeting\n  text: Conduct predictive policing or any operational law-enforcement targeting.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/crimescore-io/eligibility/crimescore-io-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from crimescore-io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Safety
- Real Estate
- Data
- Mapping
---
