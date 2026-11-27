---
api_specs:
- filename: spycloud-breach-api-openapi.yml
  format: yaml
  label: SpyCloud Breach API
  slug: spycloud-breach-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spycloud/openapi/spycloud-breach-api-openapi.yml
- filename: spycloud-check-api-openapi.yml
  format: yaml
  label: SpyCloud Check API
  slug: spycloud-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spycloud/openapi/spycloud-check-api-openapi.yml
- filename: spycloud-compass-api-openapi.yml
  format: yaml
  label: SpyCloud Compass API
  slug: spycloud-compass-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spycloud/openapi/spycloud-compass-api-openapi.yml
- filename: spycloud-data-api-openapi.yml
  format: yaml
  label: SpyCloud Data API
  slug: spycloud-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spycloud/openapi/spycloud-data-api-openapi.yml
- filename: spycloud-query-api-openapi.yml
  format: yaml
  label: SpyCloud Query API
  slug: spycloud-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spycloud/openapi/spycloud-query-api-openapi.yml
- filename: spycloud-stats-api-openapi.yml
  format: yaml
  label: SpyCloud Stats API
  slug: spycloud-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spycloud/openapi/spycloud-stats-api-openapi.yml
- filename: spycloud-watchlist-api-openapi.yml
  format: yaml
  label: SpyCloud Watchlist API
  slug: spycloud-watchlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spycloud/openapi/spycloud-watchlist-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access to the Website may not be legal by certain persons or in certain countries. If you access the Website from outside the United States, you do so on your own initiative and are responsible for compliance with local laws.
  entity_types:
  - text: By using this Website, you represent and warrant that you are of legal age to form a binding contract with the Company.
    type: individual
  minimum_age:
    text: you represent and warrant that you are of legal age to form a binding contract with the Company
    value: legal age
  restricted_uses:
  - summary: Unlawful or exploitative use
    text: Use the Website in any way that violates any applicable federal, state, local, or international law or regulation
  - summary: Impersonation
    text: Use the Website to impersonate or attempt to impersonate the Company, a Company employee, another user, or any other person or entity
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
name: SpyCloud
provenance_date: '2026-11-10'
provider_name: SpyCloud
provider_slug: spycloud
slug: spycloud-eligibility
source_date: '2026-11-10'
source_filename: spycloud-eligibility.yml
source_heading: Eligibility
source_page: https://spycloud.com/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SpyCloud\naid: spycloud\nurl: https://spycloud.com/legal/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access to the Website may not be legal by certain persons or in certain countries. If you access the Website\n    from outside the United States, you do so on your own initiative and are responsible for compliance with local\n    laws.\nentity_types:\n- type: individual\n  text: By using this Website, you represent and warrant that you are of legal age to form a binding contract with\n    the Company.\nrestricted_uses:\n- summary: Unlawful or exploitative use\n \
  \ text: Use the Website in any way that violates any applicable federal, state, local, or international law or regulation\n- summary: Impersonation\n  text: Use the Website to impersonate or attempt to impersonate the Company, a Company employee, another user,\n    or any other person or entity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: you represent and warrant that you are of legal age to form a binding contract with the Company\n"
source_yaml_url: https://artifacts.apis.io/spycloud/eligibility/spycloud-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from SpyCloud's own page on 2026-11-10.
synthetic: false
tags:
- Cybersecurity
- Threat Intelligence
- Identity
- Fraud Prevention
- Account Takeover
- Dark Web
- Breach Data
- Malware
- Authentication
- Security
---
