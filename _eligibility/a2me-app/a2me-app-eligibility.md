---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You confirm you are not in a country under US embargo and are not on any US government prohibited-party list.
  entity_types:
  - text: You must be at least 13 years old to create an account. If you are under 18, a parent or legal guardian must review these Terms with you and agree to them on your behalf
    type: individual
  - text: A parent or legal guardian may create a managed profile for a child so the child has a place in the family tree
    type: other
  minimum_age:
    text: You must be at least 13 years old to create an account.
    value: '13'
  restricted_uses:
  - summary: HIPAA, FISMA or regulated data
    text: use the Services for any purpose that is subject to HIPAA, FISMA or similar regulated data rules
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may choose to verify your identity through our provider, Persona. Verification is optional, grants a badge, and may be required for certain features such as payouts.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: A2Me
provenance_date: '2026-11-09'
provider_name: A2Me
provider_slug: a2me-app
slug: a2me-app-eligibility
source_date: '2026-11-09'
source_filename: a2me-app-eligibility.yml
source_heading: Eligibility
source_page: https://a2me.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: A2Me\naid: a2me-app\nurl: https://a2me.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You confirm you are not in a country under US embargo and are not on any US government prohibited-party\n    list.\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to create an account. If you are under 18, a parent or legal guardian\n    must review these Terms with you and agree to them on your behalf\n- type: other\n  text: A parent or legal guardian may create a managed profile for a child so the child has a place in the family\n    tree\nrestricted_uses:\n\
  - summary: HIPAA, FISMA or regulated data\n  text: use the Services for any purpose that is subject to HIPAA, FISMA or similar regulated data rules\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may choose to verify your identity through our provider, Persona. Verification is optional, grants a\n    badge, and may be required for certain features such as payouts.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/a2me-app/eligibility/a2me-app-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from A2Me's own page on 2026-11-09.
synthetic: false
tags:
- Family
- Social
- Legacy
- Photo Sharing
- Mobile App
---
