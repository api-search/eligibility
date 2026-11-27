---
api_specs:
- filename: avoma-calls-api-openapi.yml
  format: yaml
  label: Avoma Calls API
  slug: avoma-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoma/openapi/avoma-calls-api-openapi.yml
- filename: avoma-custom-category-api-openapi.yml
  format: yaml
  label: Avoma Custom Category API
  slug: avoma-custom-category-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoma/openapi/avoma-custom-category-api-openapi.yml
- filename: avoma-engagement-analytics-api-openapi.yml
  format: yaml
  label: Avoma Engagement Analytics API
  slug: avoma-engagement-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoma/openapi/avoma-engagement-analytics-api-openapi.yml
- filename: avoma-meeting-outcomes-api-openapi.yml
  format: yaml
  label: Avoma Meeting Outcomes API
  slug: avoma-meeting-outcomes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoma/openapi/avoma-meeting-outcomes-api-openapi.yml
- filename: avoma-meeting-types-api-openapi.yml
  format: yaml
  label: Avoma Meeting Types API
  slug: avoma-meeting-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoma/openapi/avoma-meeting-types-api-openapi.yml
- filename: avoma-meetings-api-openapi.yml
  format: yaml
  label: Avoma Meetings API
  slug: avoma-meetings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoma/openapi/avoma-meetings-api-openapi.yml
- filename: avoma-meetings-sentiments-api-openapi.yml
  format: yaml
  label: Avoma Meetings Sentiments API
  slug: avoma-meetings-sentiments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoma/openapi/avoma-meetings-sentiments-api-openapi.yml
- filename: avoma-notes-api-openapi.yml
  format: yaml
  label: Avoma Notes API
  slug: avoma-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoma/openapi/avoma-notes-api-openapi.yml
- filename: avoma-recording-api-openapi.yml
  format: yaml
  label: Avoma Recording API
  slug: avoma-recording-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoma/openapi/avoma-recording-api-openapi.yml
- filename: avoma-revenue-intelligence-beta-api-openapi.yml
  format: yaml
  label: Avoma Revenue Intelligence [Beta] API
  slug: avoma-revenue-intelligence-beta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoma/openapi/avoma-revenue-intelligence-beta-api-openapi.yml
- filename: avoma-scorecard-evaluations-api-openapi.yml
  format: yaml
  label: Avoma Scorecard Evaluations API
  slug: avoma-scorecard-evaluations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoma/openapi/avoma-scorecard-evaluations-api-openapi.yml
- filename: avoma-scorecards-api-openapi.yml
  format: yaml
  label: Avoma Scorecards API
  slug: avoma-scorecards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoma/openapi/avoma-scorecards-api-openapi.yml
- filename: avoma-smart-category-api-openapi.yml
  format: yaml
  label: Avoma Smart Category API
  slug: avoma-smart-category-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoma/openapi/avoma-smart-category-api-openapi.yml
- filename: avoma-snippets-api-openapi.yml
  format: yaml
  label: Avoma Snippets API
  slug: avoma-snippets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoma/openapi/avoma-snippets-api-openapi.yml
- filename: avoma-templates-api-openapi.yml
  format: yaml
  label: Avoma Templates API
  slug: avoma-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoma/openapi/avoma-templates-api-openapi.yml
- filename: avoma-transcriptions-api-openapi.yml
  format: yaml
  label: Avoma Transcriptions API
  slug: avoma-transcriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoma/openapi/avoma-transcriptions-api-openapi.yml
- filename: avoma-users-api-openapi.yml
  format: yaml
  label: Avoma Users API
  slug: avoma-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoma/openapi/avoma-users-api-openapi.yml
- filename: avoma-webhooks-api-openapi.yml
  format: yaml
  label: Avoma Webhooks API
  slug: avoma-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avoma/openapi/avoma-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'By accessing the Services, you represent and warrant that: You are not under eighteen (18) years of age.'
    type: individual
  - text: If you elect to use Services in connection with your employment or your work for a third party, you also represent and warrant that you have all rights, authority, permission, and third party approvals necessary to provide us with all of the Content.
    type: business
  minimum_age:
    text: You are not under eighteen (18) years of age.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We reserve the right to refuse registration of, or to cancel, a User ID at our discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Avoma
provenance_date: '2026-11-09'
provider_name: Avoma
provider_slug: avoma
slug: avoma-eligibility
source_date: '2026-11-09'
source_filename: avoma-eligibility.yml
source_heading: Eligibility
source_page: https://www.avoma.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avoma\naid: avoma\nurl: https://www.avoma.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'By accessing the Services, you represent and warrant that: You are not under eighteen (18) years of age.'\n- type: business\n  text: If you elect to use Services in connection with your employment or your work for a third party, you also\n    represent and warrant that you have all rights, authority, permission, and third party approvals necessary to\n    provide us with all of the Content.\nrestricted_uses: []\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: We reserve the right to refuse registration of, or to cancel, a User ID at our discretion.\nminimum_age:\n  value: '18'\n  text: You are not under eighteen (18) years of age.\n"
source_yaml_url: https://artifacts.apis.io/avoma/eligibility/avoma-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Avoma's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Meeting Assistant
- Sales Enablement
- Automation
- Productivity
---
