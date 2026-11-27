---
api_specs:
- filename: levelblue-alarms-api-openapi.yml
  format: yaml
  label: LevelBlue Alarms API
  slug: levelblue-alarms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/levelblue/openapi/levelblue-alarms-api-openapi.yml
- filename: levelblue-events-api-openapi.yml
  format: yaml
  label: LevelBlue Events API
  slug: levelblue-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/levelblue/openapi/levelblue-events-api-openapi.yml
- filename: levelblue-oauth-api-openapi.yml
  format: yaml
  label: LevelBlue O Auth API
  slug: levelblue-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/levelblue/openapi/levelblue-oauth-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Access from jurisdictions where illegal
    text: Access to our Site content or materials from jurisdictions where such access is illegal is prohibited.
  - summary: Export law violations
    text: You may not use or export the materials on this Site in violation of any export laws and regulations.
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
name: LevelBlue
provenance_date: '2026-11-09'
provider_name: LevelBlue
provider_slug: levelblue
slug: levelblue-eligibility
source_date: '2026-11-09'
source_filename: levelblue-eligibility.yml
source_heading: Eligibility
source_page: https://www.levelblue.com/legal/website-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LevelBlue\naid: levelblue\nurl: https://www.levelblue.com/legal/website-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Access from jurisdictions where illegal\n  text: Access to our Site content or materials from jurisdictions where such access is illegal is prohibited.\n- summary: Export law violations\n  text: You may not use or export the materials on this Site in violation of any export laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/levelblue/eligibility/levelblue-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from LevelBlue's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Cybersecurity
- Security
- Threat Intelligence
- Managed Security
- SIEM
- Threat Detection
- Incident Response
- Compliance
---
