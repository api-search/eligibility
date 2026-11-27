---
api_specs:
- filename: chronogg-attributions-api-openapi.yml
  format: yaml
  label: Chronogg Attributions API
  slug: chronogg-attributions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chronogg/openapi/chronogg-attributions-api-openapi.yml
- filename: chronogg-bounties-api-openapi.yml
  format: yaml
  label: Chronogg Bounties API
  slug: chronogg-bounties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chronogg/openapi/chronogg-bounties-api-openapi.yml
- filename: chronogg-chronogg-api-api-openapi.yml
  format: yaml
  label: Chronogg Chronogg API
  slug: chronogg-chronogg-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chronogg/openapi/chronogg-chronogg-api-api-openapi.yml
- filename: chronogg-code-api-openapi.yml
  format: yaml
  label: Chronogg Code API
  slug: chronogg-code-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chronogg/openapi/chronogg-code-api-openapi.yml
- filename: chronogg-complete-reward-api-openapi.yml
  format: yaml
  label: Chronogg Complete Reward API
  slug: chronogg-complete-reward-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chronogg/openapi/chronogg-complete-reward-api-openapi.yml
- filename: chronogg-event-api-openapi.yml
  format: yaml
  label: Chronogg Event API
  slug: chronogg-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chronogg/openapi/chronogg-event-api-openapi.yml
- filename: chronogg-manage-api-openapi.yml
  format: yaml
  label: Chronogg Manage API
  slug: chronogg-manage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chronogg/openapi/chronogg-manage-api-openapi.yml
- filename: chronogg-member-api-openapi.yml
  format: yaml
  label: Chronogg Member API
  slug: chronogg-member-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chronogg/openapi/chronogg-member-api-openapi.yml
- filename: chronogg-player-api-openapi.yml
  format: yaml
  label: Chronogg Player API
  slug: chronogg-player-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chronogg/openapi/chronogg-player-api-openapi.yml
- filename: chronogg-rewards-api-openapi.yml
  format: yaml
  label: Chronogg Rewards API
  slug: chronogg-rewards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chronogg/openapi/chronogg-rewards-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: we prohibit access to Nexus in certain geographic locations; These restrictions generally prohibit transactions involving certain areas (e.g. Crimea, Cuba, Iran, North Korea, and Syria)
  entity_types:
  - text: Persons who are at or above the legal age of majority in their jurisdiction (18 years old in most states) who agree to be bound by all of the Terms
    type: individual
  minimum_age:
    text: Persons who are at or above the legal age of majority in their jurisdiction (18 years old in most states)
    value: '18'
  restricted_uses:
  - summary: No AI system input or training
    text: You specifically agree not to input, upload, or otherwise provide any Service Content to any AI System
  - summary: Sanctioned jurisdictions
    text: we prohibit access to Nexus in certain geographic locations
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Program Eligible Creators may be required to link their YouTube/Twitch or other social media account to verify their identity.
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Chronogg
provenance_date: '2026-11-09'
provider_name: Chronogg
provider_slug: chronogg
slug: chronogg-eligibility
source_date: '2026-11-09'
source_filename: chronogg-eligibility.yml
source_heading: Eligibility
source_page: https://www.nexus.gg/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chronogg\naid: chronogg\nurl: https://www.nexus.gg/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: we prohibit access to Nexus in certain geographic locations; These restrictions generally prohibit transactions\n    involving certain areas (e.g. Crimea, Cuba, Iran, North Korea, and Syria)\nentity_types:\n- type: individual\n  text: Persons who are at or above the legal age of majority in their jurisdiction (18 years old in most states)\n    who agree to be bound by all of the Terms\nrestricted_uses:\n- summary: No\
  \ AI system input or training\n  text: You specifically agree not to input, upload, or otherwise provide any Service Content to any AI System\n- summary: Sanctioned jurisdictions\n  text: we prohibit access to Nexus in certain geographic locations\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Program Eligible Creators may be required to link their YouTube/Twitch or other social media account to\n    verify their identity.\nminimum_age:\n  value: '18'\n  text: Persons who are at or above the legal age of majority in their jurisdiction (18 years old in most states)\n"
source_yaml_url: https://artifacts.apis.io/chronogg/eligibility/chronogg-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Chronogg's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
