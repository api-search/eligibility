---
api_specs:
- filename: appsmith-applications-api-openapi.yml
  format: yaml
  label: Appsmith Applications API
  slug: appsmith-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsmith/openapi/appsmith-applications-api-openapi.yml
- filename: appsmith-workspaces-api-openapi.yml
  format: yaml
  label: Appsmith Workspaces API
  slug: appsmith-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsmith/openapi/appsmith-workspaces-api-openapi.yml
- filename: appsmith-data-sources-api-openapi.yml
  format: yaml
  label: Appsmith Data Sources API
  slug: appsmith-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsmith/openapi/appsmith-data-sources-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Export clause: Platform not to be shipped or re-exported to proscribed or embargoed countries or their nationals, without naming specific countries.'
  entity_types:
  - text: YOU AND THE ENTITY YOU REPRESENT (“CUSTOMER”) AGREE TO BE BOUND BY THIS AGREEMENT
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Nuclear, chemical/biological, missile uses
    text: 'nor will it be used for: nuclear activities, chemical or biological weapons, or missile projects unless authorized by the U.S. government.'
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
name: Appsmith
provenance_date: '2026-11-09'
provider_name: Appsmith
provider_slug: appsmith
slug: appsmith-eligibility
source_date: '2026-11-09'
source_filename: appsmith-eligibility.yml
source_heading: Eligibility
source_page: https://www.appsmith.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Appsmith\naid: appsmith\nurl: https://www.appsmith.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Export clause: Platform not to be shipped or re-exported to proscribed or embargoed countries or their\n    nationals, without naming specific countries.'\nentity_types:\n- type: business\n  text: YOU AND THE ENTITY YOU REPRESENT (“CUSTOMER”) AGREE TO BE BOUND BY THIS AGREEMENT\nrestricted_uses:\n- summary: Nuclear, chemical/biological, missile uses\n  text: 'nor will it be used for: nuclear activities, chemical or biological weapons, or missile projects unless\n\
  \    authorized by the U.S. government.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/appsmith/eligibility/appsmith-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Appsmith's own page on 2026-11-09.
synthetic: false
tags:
- Low-Code
- Open Source
- Internal Tools
- Workflow Automation
- Developer Tools
---
