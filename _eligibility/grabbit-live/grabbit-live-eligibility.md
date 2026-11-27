---
api_specs:
- filename: grabbit-live-account-api-openapi.yml
  format: yaml
  label: grabbit-live Account API
  slug: grabbit-live-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grabbit-live/openapi/grabbit-live-account-api-openapi.yml
- filename: grabbit-live-grabs-api-openapi.yml
  format: yaml
  label: grabbit-live Grabs API
  slug: grabbit-live-grabs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grabbit-live/openapi/grabbit-live-grabs-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: use it if you are located in an embargoed jurisdiction or are listed on a US government restricted-party list
  entity_types:
  - text: the individual or entity using the service
    type: individual
  - text: If you use Grabbit on behalf of an organization, you represent that you have authority to bind that organization
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export controls and sanctions
    text: use the Service in violation of United States export control or economic sanctions laws
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
name: grabbit-live
provenance_date: '2026-11-09'
provider_name: grabbit-live
provider_slug: grabbit-live
slug: grabbit-live-eligibility
source_date: '2026-11-09'
source_filename: grabbit-live-eligibility.yml
source_heading: Eligibility
source_page: https://www.grabbit.live/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: grabbit-live\naid: grabbit-live\nurl: https://www.grabbit.live/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: use it if you are located in an embargoed jurisdiction or are listed on a US government restricted-party\n    list\nentity_types:\n- type: individual\n  text: the individual or entity using the service\n- type: business\n  text: If you use Grabbit on behalf of an organization, you represent that you have authority to bind that organization\nrestricted_uses:\n- summary: Export controls and sanctions\n  text: use the Service in violation of United States export control\
  \ or economic sanctions laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/grabbit-live/eligibility/grabbit-live-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from grabbit-live's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Screenshots
- AI Agents
- Automation
- Visual
---
