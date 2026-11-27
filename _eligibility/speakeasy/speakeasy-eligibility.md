---
api_specs:
- filename: speakeasy-artifacts-api-openapi.yml
  format: yaml
  label: Speakeasy Artifacts API
  slug: speakeasy-artifacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/speakeasy/openapi/speakeasy-artifacts-api-openapi.yml
- filename: speakeasy-auth-api-openapi.yml
  format: yaml
  label: Speakeasy Auth API
  slug: speakeasy-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/speakeasy/openapi/speakeasy-auth-api-openapi.yml
- filename: speakeasy-codesamples-api-openapi.yml
  format: yaml
  label: Speakeasy CodeSamples API
  slug: speakeasy-codesamples-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/speakeasy/openapi/speakeasy-codesamples-api-openapi.yml
- filename: speakeasy-events-api-openapi.yml
  format: yaml
  label: Speakeasy Events API
  slug: speakeasy-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/speakeasy/openapi/speakeasy-events-api-openapi.yml
- filename: speakeasy-github-api-openapi.yml
  format: yaml
  label: Speakeasy Github API
  slug: speakeasy-github-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/speakeasy/openapi/speakeasy-github-api-openapi.yml
- filename: speakeasy-organizations-api-openapi.yml
  format: yaml
  label: Speakeasy Organizations API
  slug: speakeasy-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/speakeasy/openapi/speakeasy-organizations-api-openapi.yml
- filename: speakeasy-publishingtokens-api-openapi.yml
  format: yaml
  label: Speakeasy PublishingTokens API
  slug: speakeasy-publishingtokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/speakeasy/openapi/speakeasy-publishingtokens-api-openapi.yml
- filename: speakeasy-reports-api-openapi.yml
  format: yaml
  label: Speakeasy Reports API
  slug: speakeasy-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/speakeasy/openapi/speakeasy-reports-api-openapi.yml
- filename: speakeasy-schemastore-api-openapi.yml
  format: yaml
  label: Speakeasy SchemaStore API
  slug: speakeasy-schemastore-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/speakeasy/openapi/speakeasy-schemastore-api-openapi.yml
- filename: speakeasy-subscriptions-api-openapi.yml
  format: yaml
  label: Speakeasy Subscriptions API
  slug: speakeasy-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/speakeasy/openapi/speakeasy-subscriptions-api-openapi.yml
- filename: speakeasy-suggest-api-openapi.yml
  format: yaml
  label: Speakeasy Suggest API
  slug: speakeasy-suggest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/speakeasy/openapi/speakeasy-suggest-api-openapi.yml
- filename: speakeasy-workspaces-api-openapi.yml
  format: yaml
  label: Speakeasy Workspaces API
  slug: speakeasy-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/speakeasy/openapi/speakeasy-workspaces-api-openapi.yml
- filename: speakeasy-short-urls-api-openapi.yml
  format: yaml
  label: Speakeasy Short URLs API
  slug: speakeasy-short-urls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/speakeasy/openapi/speakeasy-short-urls-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting these Terms on behalf of an employer or another legal entity, you represent and warrant that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Timesharing or service bureau use
    text: use the Services or any Software for timesharing or service bureau purposes or otherwise for the benefit of a third
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
name: Speakeasy
provenance_date: '2026-11-10'
provider_name: Speakeasy
provider_slug: speakeasy
slug: speakeasy-eligibility
source_date: '2026-11-10'
source_filename: speakeasy-eligibility.yml
source_heading: Eligibility
source_page: https://www.speakeasy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Speakeasy\naid: speakeasy\nurl: https://www.speakeasy.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting these Terms on behalf of an employer or another legal entity, you represent and warrant\n    that you have the authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Timesharing or service bureau use\n  text: use the Services or any Software for timesharing or service bureau purposes or otherwise for the benefit\n    of a third\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/speakeasy/eligibility/speakeasy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Speakeasy's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Documentation
- MCP
- Platform
- SDK
- Terraform
- Testing
- SDK Generation
- A2A
- OpenAPI
---
