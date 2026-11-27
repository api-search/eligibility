---
api_specs:
- filename: pingfyr-com-openapi-generated.yml
  format: yaml
  label: pingfyr-com API
  slug: pingfyr-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pingfyr-com/openapi/_ae-authored/pingfyr-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age and have the legal capacity to enter into contracts to use Pingfyr.
    type: individual
  - text: If you are using Pingfyr on behalf of an organization, you represent that you have authority to bind that organization to these terms.
    type: business
  minimum_age:
    text: You must be at least 18 years of age and have the legal capacity to enter into contracts to use Pingfyr.
    value: '18'
  restricted_uses:
  - summary: Prohibited uses
    text: 'The Pingfyr service must not be used for:'
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
name: pingfyr-com
provenance_date: '2026-11-10'
provider_name: pingfyr-com
provider_slug: pingfyr-com
slug: pingfyr-com-eligibility
source_date: '2026-11-10'
source_filename: pingfyr-com-eligibility.yml
source_heading: Eligibility
source_page: https://pingfyr.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: pingfyr-com\naid: pingfyr-com\nurl: https://pingfyr.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age and have the legal capacity to enter into contracts to use Pingfyr.\n- type: business\n  text: If you are using Pingfyr on behalf of an organization, you represent that you have authority to bind that\n    organization to these terms.\nrestricted_uses:\n- summary: Prohibited uses\n  text: 'The Pingfyr service must not be used for:'\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age and have the legal capacity to enter into contracts to use Pingfyr.\n"
source_yaml_url: https://artifacts.apis.io/pingfyr-com/eligibility/pingfyr-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from pingfyr-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Scheduling
- Notification
- Webhook
- Artificial Intelligence
---
