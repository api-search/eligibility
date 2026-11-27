---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old, or the age of majority where you live, and able to form a binding contract to use the Service.
    type: individual
  - text: If you use the Service on behalf of a company, you confirm you have authority to bind that company, and "you" includes it.
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age of majority where you live
    value: '18'
  restricted_uses:
  - summary: Sexual content involving minors
    text: Create sexual content involving minors or content that sexualizes minors in any way.
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
name: Avatar Factory
provenance_date: '2026-11-09'
provider_name: Avatar Factory
provider_slug: avatarfactory-io
slug: avatarfactory-io-eligibility
source_date: '2026-11-09'
source_filename: avatarfactory-io-eligibility.yml
source_heading: Eligibility
source_page: https://avatarfactory.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avatar Factory\naid: avatarfactory-io\nurl: https://avatarfactory.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of majority where you live, and able to form a binding contract\n    to use the Service.\n- type: business\n  text: If you use the Service on behalf of a company, you confirm you have authority to bind that company, and\n    \"you\" includes it.\nrestricted_uses:\n- summary: Sexual content involving minors\n  text: Create sexual content involving minors or content that\
  \ sexualizes minors in any way.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority where you live\n"
source_yaml_url: https://artifacts.apis.io/avatarfactory-io/eligibility/avatarfactory-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Avatar Factory's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Avatars
- Influencer
- Video
- Marketing
- Company
---
