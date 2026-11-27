---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old
    type: individual
  minimum_age:
    text: You must be at least 16 years old
    value: '16'
  restricted_uses:
  - summary: Illegal content
    text: Forward content that is illegal in the United States or the recipient's jurisdiction
  - summary: Impersonation
    text: Impersonate other individuals or organizations
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide a valid email address to create an account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ARC-Relay
provenance_date: '2026-11-09'
provider_name: ARC-Relay
provider_slug: arc-relay-com
slug: arc-relay-com-eligibility
source_date: '2026-11-09'
source_filename: arc-relay-com-eligibility.yml
source_heading: Eligibility
source_page: https://arc-relay.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ARC-Relay\naid: arc-relay-com\nurl: https://arc-relay.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old\nrestricted_uses:\n- summary: Illegal content\n  text: Forward content that is illegal in the United States or the recipient's jurisdiction\n- summary: Impersonation\n  text: Impersonate other individuals or organizations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide a valid email address to create an account\nminimum_age:\n  value: '16'\n\
  \  text: You must be at least 16 years old\n"
source_yaml_url: https://artifacts.apis.io/arc-relay-com/eligibility/arc-relay-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from ARC-Relay's own page on 2026-11-09.
synthetic: false
tags:
- Email
- Forwarding
- SRS
- Arc
- Services
---
