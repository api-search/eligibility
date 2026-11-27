---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use the Services or submit any information to us.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use the Services or submit any information to us.
    value: '18'
  restricted_uses:
  - summary: Adult content prohibited
    text: Posting or sharing adult content is strictly forbidden on KikiHub.
  - summary: Illegal activities
    text: Do not use KikiHub to engage in illegal activities or to promote dangerous behavior.
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
name: Kiki
provenance_date: '2026-11-09'
provider_name: Kiki
provider_slug: kiki
slug: kiki-eligibility
source_date: '2026-11-09'
source_filename: kiki-eligibility.yml
source_heading: Eligibility
source_page: https://kikihub.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kiki\naid: kiki\nurl: https://kikihub.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Services or submit any information to us.\nrestricted_uses:\n- summary: Adult content prohibited\n  text: Posting or sharing adult content is strictly forbidden on KikiHub.\n- summary: Illegal activities\n  text: Do not use KikiHub to engage in illegal activities or to promote dangerous behavior.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: You must be at least 18 years of age to use the Services or submit any information to us.\n"
source_yaml_url: https://artifacts.apis.io/kiki/eligibility/kiki-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Kiki's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Social
- Chat
- Dating
- Location
- Community
- Networking
- Mobile
- Messaging
---
