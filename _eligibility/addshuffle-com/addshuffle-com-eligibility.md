---
api_specs:
- filename: addshuffle-com-credits-api-openapi.yml
  format: yaml
  label: Shuffle Credits API
  slug: addshuffle-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/addshuffle-com/openapi/addshuffle-com-credits-api-openapi.yml
- filename: addshuffle-com-l402-api-openapi.yml
  format: yaml
  label: Shuffle L402 API
  slug: addshuffle-com-l402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/addshuffle-com/openapi/addshuffle-com-l402-api-openapi.yml
- filename: addshuffle-com-manual-mode-api-openapi.yml
  format: yaml
  label: Shuffle Manual Mode API
  slug: addshuffle-com-manual-mode-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/addshuffle-com/openapi/addshuffle-com-manual-mode-api-openapi.yml
- filename: addshuffle-com-utilities-api-openapi.yml
  format: yaml
  label: Shuffle Utilities API
  slug: addshuffle-com-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/addshuffle-com/openapi/addshuffle-com-utilities-api-openapi.yml
- filename: addshuffle-com-video-chain-api-openapi.yml
  format: yaml
  label: Shuffle Video Chain API
  slug: addshuffle-com-video-chain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/addshuffle-com/openapi/addshuffle-com-video-chain-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of an organization, you represent and warrant that you have the authority to bind that organization to these Terms
    type: business
  minimum_age:
    text: You must be at least 13 years of age to use the Service.
    value: '13'
  restricted_uses:
  - summary: Adult content features
    text: You must be at least 18 years of age to access uncensored or adult content features.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Age verification via government-issued identification is required before these features are enabled.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Shuffle
provenance_date: '2026-11-09'
provider_name: Shuffle
provider_slug: addshuffle-com
slug: addshuffle-com-eligibility
source_date: '2026-11-09'
source_filename: addshuffle-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.textshuffle.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shuffle\naid: addshuffle-com\nurl: https://www.textshuffle.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of an organization, you represent and warrant that you have the authority\n    to bind that organization to these Terms\nrestricted_uses:\n- summary: Adult content features\n  text: You must be at least 18 years of age to access uncensored or adult content features.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Age verification via government-issued identification\
  \ is required before these features are enabled.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/addshuffle-com/eligibility/addshuffle-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Shuffle's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Social Media
- Automation
- Marketing
- Software-as-a-Service
---
