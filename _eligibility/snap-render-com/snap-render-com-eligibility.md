---
api_specs:
- filename: snap-render-com-extract-api-openapi.yml
  format: yaml
  label: snap-render-com Extract API
  slug: snap-render-com-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snap-render-com/openapi/snap-render-com-extract-api-openapi.yml
- filename: snap-render-com-health-api-openapi.yml
  format: yaml
  label: snap-render-com Health API
  slug: snap-render-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snap-render-com/openapi/snap-render-com-health-api-openapi.yml
- filename: snap-render-com-schedules-api-openapi.yml
  format: yaml
  label: snap-render-com Schedules API
  slug: snap-render-com-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snap-render-com/openapi/snap-render-com-schedules-api-openapi.yml
- filename: snap-render-com-usage-api-openapi.yml
  format: yaml
  label: snap-render-com Usage API
  slug: snap-render-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snap-render-com/openapi/snap-render-com-usage-api-openapi.yml
- filename: snap-render-com-webhooks-api-openapi.yml
  format: yaml
  label: snap-render-com Webhooks API
  slug: snap-render-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snap-render-com/openapi/snap-render-com-webhooks-api-openapi.yml
- filename: snap-render-com-screenshot-api-openapi.yml
  format: yaml
  label: SnapRender Screenshot API
  slug: snap-render-com-screenshot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snap-render-com/openapi/snap-render-com-screenshot-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: SnapRender makes no representation that the Service is appropriate or available for use in any particular jurisdiction.
  entity_types:
  - text: You represent and warrant that you are at least 18 years of age (or the age of legal majority in your jurisdiction) and have the legal capacity to enter into this agreement.
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent and warrant that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You represent and warrant that you are at least 18 years of age (or the age of legal majority in your jurisdiction)
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must register for an account to use the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SnapRender
provenance_date: '2026-11-10'
provider_name: SnapRender
provider_slug: snap-render-com
slug: snap-render-com-eligibility
source_date: '2026-11-10'
source_filename: snap-render-com-eligibility.yml
source_heading: Eligibility
source_page: https://snap-render.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SnapRender\naid: snap-render-com\nurl: https://snap-render.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: SnapRender makes no representation that the Service is appropriate or available for use in any particular\n    jurisdiction.\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least 18 years of age (or the age of legal majority in your jurisdiction)\n    and have the legal capacity to enter into this agreement.\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent and warrant that you\
  \ have the authority\n    to bind that organization to these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must register for an account to use the Service.\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least 18 years of age (or the age of legal majority in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/snap-render-com/eligibility/snap-render-com-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 5 quoted statements, read from SnapRender's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Screenshots
- Rendering
- Automation
- Cloud
---
