---
api_specs:
- filename: sanas-stream-asyncapi.yml
  format: yaml
  label: Sanas Stream API
  slug: sanas-stream-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/sanas/asyncapi/sanas-stream-asyncapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We do not assert that the Services or any Sanas Content is accessible or suitable outside of the United States. By using the Services, you confirm that you are not located in... any country or region that is subject to U.S. government embargoes or sanctions.
  entity_types:
  - text: The Services are offered and available to users who are 18 years of age or older.
    type: individual
  - text: If you are acting on behalf of a person or entity, you affirm that you possess the authority to accept these Terms on behalf of such party
    type: business
  minimum_age:
    text: The Services are offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Unlawful or sanctioned use
    text: You are obligated to use the Services solely for lawful purposes and in adherence to these Terms.
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
name: Sanas
provenance_date: '2026-11-10'
provider_name: Sanas
provider_slug: sanas
slug: sanas-eligibility
source_date: '2026-11-10'
source_filename: sanas-eligibility.yml
source_heading: Eligibility
source_page: https://www.sanas.ai/legal-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sanas\naid: sanas\nurl: https://www.sanas.ai/legal-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We do not assert that the Services or any Sanas Content is accessible or suitable outside of the United\n    States. By using the Services, you confirm that you are not located in... any country or region that is subject\n    to U.S. government embargoes or sanctions.\nentity_types:\n- type: individual\n  text: The Services are offered and available to users who are 18 years of age or older.\n- type: business\n  text: If you are acting on behalf of a person or entity, you affirm\
  \ that you possess the authority to accept these\n    Terms on behalf of such party\nrestricted_uses:\n- summary: Unlawful or sanctioned use\n  text: You are obligated to use the Services solely for lawful purposes and in adherence to these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/sanas/eligibility/sanas-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Sanas's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Speech AI
- Voice AI
- Accent Translation
- Language Translation
- Speech Enhancement
- Real-Time Audio
- SDK
- WebSocket
- Contact Center
- Real-Time
---
