---
api_specs:
- filename: aboard-sh-openapi-generated.yml
  format: yaml
  label: Aboard API
  slug: aboard-sh-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aboard-sh/openapi/_ae-authored/aboard-sh-openapi-generated.yml
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
  - summary: Unlawful, harassing, intrusive or spam use
    text: Do not use Aboard to send unlawful content, to harass anyone, to break into anything, or to relay spam through its webhooks.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in with an email link.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aboard
provenance_date: '2026-11-09'
provider_name: Aboard
provider_slug: aboard-sh
slug: aboard-sh-eligibility
source_date: '2026-11-09'
source_filename: aboard-sh-eligibility.yml
source_heading: Eligibility
source_page: https://aboard.sh/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aboard\naid: aboard-sh\nurl: https://aboard.sh/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful, harassing, intrusive or spam use\n  text: Do not use Aboard to send unlawful content, to harass anyone, to break into anything, or to relay spam through\n    its webhooks.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You sign in with an email link.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aboard-sh/eligibility/aboard-sh-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Aboard's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Collaboration
- Chat
- Agents
- Platform
---
