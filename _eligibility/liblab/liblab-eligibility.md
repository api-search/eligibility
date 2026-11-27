---
api_specs:
- filename: liblab-api-docs-api-openapi.yml
  format: yaml
  label: Liblab Api Docs API
  slug: liblab-api-docs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liblab/openapi/liblab-api-docs-api-openapi.yml
- filename: liblab-api-json-api-openapi.yml
  format: yaml
  label: Liblab Api Json API
  slug: liblab-api-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liblab/openapi/liblab-api-json-api-openapi.yml
- filename: liblab-collections-api-openapi.yml
  format: yaml
  label: Liblab Collections API
  slug: liblab-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liblab/openapi/liblab-collections-api-openapi.yml
- filename: liblab-docs-api-openapi.yml
  format: yaml
  label: Liblab Docs API
  slug: liblab-docs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liblab/openapi/liblab-docs-api-openapi.yml
- filename: liblab-github-linguist-api-openapi.yml
  format: yaml
  label: Liblab Github Linguist API
  slug: liblab-github-linguist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liblab/openapi/liblab-github-linguist-api-openapi.yml
- filename: liblab-liblab-api-api-openapi.yml
  format: yaml
  label: Liblab Liblab API
  slug: liblab-liblab-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liblab/openapi/liblab-liblab-api-api-openapi.yml
- filename: liblab-liblaber-api-openapi.yml
  format: yaml
  label: Liblab Liblaber API
  slug: liblab-liblaber-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liblab/openapi/liblab-liblaber-api-openapi.yml
- filename: liblab-schema-api-openapi.yml
  format: yaml
  label: Liblab Schema API
  slug: liblab-schema-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liblab/openapi/liblab-schema-api-openapi.yml
- filename: liblab-open-api-api-openapi.yml
  format: yaml
  label: Liblab Open API
  slug: liblab-open-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liblab/openapi/liblab-open-api-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services if you are a person barred from receiving the Services under the laws of the United States or other countries, including the country in which you are resident or from which you use the Services.
  entity_types:
  - text: If you are registering for or using the Services on behalf of an organization, you are agreeing to these Terms for that organization and promising that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years of age (or the age of legal majority in your jurisdiction if different than 18) to be eligible to use the Services.
    value: '18'
  restricted_uses:
  - summary: Competitors
    text: You may not access the Services if you are a competitor of liblab, except with liblab’s prior written consent.
  - summary: Open source free tier not for profit
    text: You are prohibited from using Open Source Developer/Free Services at any time for any for-profit endeavors.
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
name: Liblab
provenance_date: '2026-11-09'
provider_name: Liblab
provider_slug: liblab
slug: liblab-eligibility
source_date: '2026-11-09'
source_filename: liblab-eligibility.yml
source_heading: Eligibility
source_page: https://liblab.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Liblab\naid: liblab\nurl: https://liblab.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services if you are a person barred from receiving the Services under the laws of the\n    United States or other countries, including the country in which you are resident or from which you use the\n    Services.\nentity_types:\n- type: business\n  text: If you are registering for or using the Services on behalf of an organization, you are agreeing to these\n    Terms for that organization and promising that you have the authority to bind that organization to these\
  \ Terms.\nrestricted_uses:\n- summary: Competitors\n  text: You may not access the Services if you are a competitor of liblab, except with liblab’s prior written consent.\n- summary: Open source free tier not for profit\n  text: You are prohibited from using Open Source Developer/Free Services at any time for any for-profit endeavors.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age (or the age of legal majority in your jurisdiction if different than\n    18) to be eligible to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/liblab/eligibility/liblab-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Liblab's own page on 2026-11-09.
synthetic: false
tags:
- SDK
- SDK Generation
- Code Generation
- OpenAPI
- Developer Tools
- MCP
- AI Agents
- Postman
- Terraform
- Developer Experience
---
