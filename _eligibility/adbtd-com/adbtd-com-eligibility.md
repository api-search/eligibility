---
api_specs:
- filename: adbtd-com-openapi-generated.yml
  format: yaml
  label: adbtd API
  slug: adbtd-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adbtd-com/openapi/_ae-authored/adbtd-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are at least eighteen (18) years of age and that you possess the legal capacity to enter into a binding contract.
    type: individual
  - text: As a general principle, a single workspace is intended to correspond to a single legal entity.
    type: business
  minimum_age:
    text: You represent and warrant that you are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Abusive or unlawful mail flows
    text: to operate any mail flow that contravenes the laws applicable to you, to your recipients, or to the French Republic.
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
name: adbtd
provenance_date: '2026-11-09'
provider_name: adbtd
provider_slug: adbtd-com
slug: adbtd-com-eligibility
source_date: '2026-11-09'
source_filename: adbtd-com-eligibility.yml
source_heading: Eligibility
source_page: https://adbtd.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: adbtd\naid: adbtd-com\nurl: https://adbtd.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least eighteen (18) years of age and that you possess the legal\n    capacity to enter into a binding contract.\n- type: business\n  text: As a general principle, a single workspace is intended to correspond to a single legal entity.\nrestricted_uses:\n- summary: Abusive or unlawful mail flows\n  text: to operate any mail flow that contravenes the laws applicable to you, to your recipients, or\
  \ to the French\n    Republic.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/adbtd-com/eligibility/adbtd-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from adbtd's own page on 2026-11-09.
synthetic: false
tags:
- Email Infrastructure
- SMTP
- IMAP
- Dedicated IP
- Deliverability
- Webhook
- MCP
---
