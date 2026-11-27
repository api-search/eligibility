---
api_specs:
- filename: jottacloud-openapi-generated.yml
  format: yaml
  label: Jottacloud API
  slug: jottacloud-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jottacloud/openapi/_ae-authored/jottacloud-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A business, organization or individual can create a Business account.
    type: business
  minimum_age:
    text: The age limit for establishing a Free account, Individual or Family account is 13 years.
    value: 13 years
  restricted_uses:
  - summary: No commercial data storage on individual/family accounts
    text: The Individual accounts and Family accounts cannot be used to store data for commercial purposes.
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
name: Jottacloud
provenance_date: '2026-11-09'
provider_name: Jottacloud
provider_slug: jottacloud
slug: jottacloud-eligibility
source_date: '2026-11-09'
source_filename: jottacloud-eligibility.yml
source_heading: Eligibility
source_page: https://jottacloud.com/en/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jottacloud\naid: jottacloud\nurl: https://jottacloud.com/en/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: A business, organization or individual can create a Business account.\nrestricted_uses:\n- summary: No commercial data storage on individual/family accounts\n  text: The Individual accounts and Family accounts cannot be used to store data for commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: 13 years\n  text: The age limit for establishing\
  \ a Free account, Individual or Family account is 13 years.\n"
source_yaml_url: https://artifacts.apis.io/jottacloud/eligibility/jottacloud-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Jottacloud's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud Storage
- Backup
- Norwegian
- Renewable Energy
---
