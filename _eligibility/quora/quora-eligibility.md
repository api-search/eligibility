---
api_specs:
- filename: quora-models-api-openapi.yml
  format: yaml
  label: Quora Models API
  slug: quora-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quora/openapi/quora-models-api-openapi.yml
- filename: quora-responses-api-openapi.yml
  format: yaml
  label: Quora Responses API
  slug: quora-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quora/openapi/quora-responses-api-openapi.yml
- filename: quora-usage-api-openapi.yml
  format: yaml
  label: Quora Usage API
  slug: quora-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quora/openapi/quora-usage-api-openapi.yml
- filename: quora-chat-completions-api-openapi.yml
  format: yaml
  label: Quora Chat Completions API
  slug: quora-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quora/openapi/quora-chat-completions-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may create an account on Quora to represent a legally incorporated business or other organization.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Not all organization accounts will be verified, though we may ask company accounts to provide verification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Quora
provenance_date: '2026-11-10'
provider_name: Quora
provider_slug: quora
slug: quora-eligibility
source_date: '2026-11-10'
source_filename: quora-eligibility.yml
source_heading: Eligibility
source_page: https://help.quora.com/hc/en-us/articles/360000470706-Platform-Policies
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Quora\naid: quora\nurl: https://help.quora.com/hc/en-us/articles/360000470706-Platform-Policies\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You may create an account on Quora to represent a legally incorporated business or other organization.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Not all organization accounts will be verified, though we may ask company accounts to provide verification.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/quora/eligibility/quora-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Quora's own page on 2026-11-10.
synthetic: false
tags:
- Community
- Knowledge
- Q&A
---
