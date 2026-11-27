---
api_specs:
- filename: thread-page-endpoint-urls-api-openapi.yml
  format: yaml
  label: ThreadPage Endpoint URLs API
  slug: thread-page-endpoint-urls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thread-page/openapi/thread-page-endpoint-urls-api-openapi.yml
- filename: thread-page-events-api-openapi.yml
  format: yaml
  label: ThreadPage Events API
  slug: thread-page-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thread-page/openapi/thread-page-events-api-openapi.yml
- filename: thread-page-integration-api-api-openapi.yml
  format: yaml
  label: ThreadPage Integration API
  slug: thread-page-integration-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thread-page/openapi/thread-page-integration-api-api-openapi.yml
- filename: thread-page-requests-api-openapi.yml
  format: yaml
  label: ThreadPage Requests API
  slug: thread-page-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thread-page/openapi/thread-page-requests-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The included AI is available only in the countries and regions where Anthropic offers its model, as its Supported Regions Policy lists them
  entity_types:
  - text: You must be at least 18 and legally able to enter into these Terms.
    type: individual
  - text: If acting for an organisation, you must have authority to do so.
    type: business
  minimum_age:
    text: You must be at least 18 and legally able to enter into these Terms.
    value: '18'
  restricted_uses:
  - summary: Prohibited content
    text: Do not store or share child sexual exploitation or abuse material.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We do not verify age.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ThreadPage
provenance_date: '2026-11-10'
provider_name: ThreadPage
provider_slug: thread-page
slug: thread-page-eligibility
source_date: '2026-11-10'
source_filename: thread-page-eligibility.yml
source_heading: Eligibility
source_page: https://thread.page/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ThreadPage\naid: thread-page\nurl: https://thread.page/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The included AI is available only in the countries and regions where Anthropic offers its model, as its\n    Supported Regions Policy lists them\nentity_types:\n- type: individual\n  text: You must be at least 18 and legally able to enter into these Terms.\n- type: business\n  text: If acting for an organisation, you must have authority to do so.\nrestricted_uses:\n- summary: Prohibited content\n  text: Do not store or share child sexual exploitation or\
  \ abuse material.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We do not verify age.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and legally able to enter into these Terms.\n"
source_yaml_url: https://artifacts.apis.io/thread-page/eligibility/thread-page-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from ThreadPage's own page on 2026-11-10.
synthetic: false
tags:
- Notes
- Collaboration
- Productivity
- Artificial Intelligence
- Web App
---
