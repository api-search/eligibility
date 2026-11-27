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
  - summary: No offering of services
    text: Users are prohibited from using KikiHub to offer any services, whether paid or free.
  - summary: No adult content
    text: Posting or sharing adult content is strictly forbidden on KikiHub.
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
provider_slug: kiki-social
slug: kiki-social-eligibility
source_date: '2026-11-09'
source_filename: kiki-social-eligibility.yml
source_heading: Eligibility
source_page: https://kikihub.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kiki\naid: kiki-social\nurl: https://kikihub.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Services or submit any information to us.\nrestricted_uses:\n- summary: No offering of services\n  text: Users are prohibited from using KikiHub to offer any services, whether paid or free.\n- summary: No adult content\n  text: Posting or sharing adult content is strictly forbidden on KikiHub.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: You must be at least 18 years of age to use the Services or submit any information to us.\n"
source_yaml_url: https://artifacts.apis.io/kiki-social/eligibility/kiki-social-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Kiki's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Social
- Mobile
- Networking
- Community
---
