---
api_specs:
- filename: usertesting-clip-api-openapi.yml
  format: yaml
  label: UserTesting Clip API
  slug: usertesting-clip-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usertesting/openapi/usertesting-clip-api-openapi.yml
- filename: usertesting-general-session-data-api-openapi.yml
  format: yaml
  label: UserTesting General Session Data API
  slug: usertesting-general-session-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usertesting/openapi/usertesting-general-session-data-api-openapi.yml
- filename: usertesting-highlightreel-api-openapi.yml
  format: yaml
  label: UserTesting Highlightreel API
  slug: usertesting-highlightreel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usertesting/openapi/usertesting-highlightreel-api-openapi.yml
- filename: usertesting-qxscore-data-api-openapi.yml
  format: yaml
  label: UserTesting QXscore Data API
  slug: usertesting-qxscore-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usertesting/openapi/usertesting-qxscore-data-api-openapi.yml
- filename: usertesting-session-api-openapi.yml
  format: yaml
  label: UserTesting Session API
  slug: usertesting-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usertesting/openapi/usertesting-session-api-openapi.yml
- filename: usertesting-studies-api-openapi.yml
  format: yaml
  label: UserTesting Studies API
  slug: usertesting-studies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usertesting/openapi/usertesting-studies-api-openapi.yml
- filename: usertesting-video-data-api-openapi.yml
  format: yaml
  label: UserTesting Video Data API
  slug: usertesting-video-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usertesting/openapi/usertesting-video-data-api-openapi.yml
- filename: usertesting-workspaces-api-openapi.yml
  format: yaml
  label: UserTesting Workspaces API
  slug: usertesting-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usertesting/openapi/usertesting-workspaces-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “ Purpose ” means Customer’s internal business use
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Embargoed or restricted countries
    text: Customer will not and nor will it permit (a) any User or any third party to access or use the Products or Services in a USA-embargoed or otherwise restricted country or region
  - summary: Testing with minors
    text: Customer is prohibited from testing with minors unless they have entered into a currently valid Minor Testing Addendum with UserTesting.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: UserTesting may accept Orders under this Agreement in its sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: UserTesting
provenance_date: '2026-11-10'
provider_name: UserTesting
provider_slug: usertesting
slug: usertesting-eligibility
source_date: '2026-11-10'
source_filename: usertesting-eligibility.yml
source_heading: Eligibility
source_page: https://www.usertesting.com/privacy-center/terms-archive
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UserTesting\naid: usertesting\nurl: https://www.usertesting.com/privacy-center/terms-archive\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: “ Purpose ” means Customer’s internal business use\nrestricted_uses:\n- summary: Embargoed or restricted countries\n  text: Customer will not and nor will it permit (a) any User or any third party to access or use the Products or\n    Services in a USA-embargoed or otherwise restricted country or region\n- summary: Testing with minors\n  text: Customer is prohibited from testing with minors unless\
  \ they have entered into a currently valid Minor Testing\n    Addendum with UserTesting.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: UserTesting may accept Orders under this Agreement in its sole discretion.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/usertesting/eligibility/usertesting-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from UserTesting's own page on 2026-11-10.
synthetic: false
tags:
- Company
- User Research
- Usability Testing
- Human Insight
- Customer Experience
- Surveys
- Video
- Transcripts
- Experience Metrics
---
