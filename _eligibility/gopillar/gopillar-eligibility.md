---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To register on the Portal, Users must be at least 18 years old.
    type: individual
  - text: Users who expect to use GoPillar’s service more than once may choose to convert their Client account into a Business Client account by subscribing to the relevant monthly plan
    type: business
  - text: It may be activated by a User possessing the experience and professional qualifications required in architectural design.
    type: developer
  minimum_age:
    text: To register on the Portal, Users must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Design Ideas are not final architectural solutions
    text: GoPillar does not provide final/executive architectural solutions and is intended solely as a means of obtaining general guidance on possible interior and/or exterior design solutions
  - summary: Prohibited Content types
    text: is pornographic, obscene or child-pornographic;
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: GoPillar reserves the right to request an identity document to verify personal data.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: GoPillar
provenance_date: '2026-11-09'
provider_name: GoPillar
provider_slug: gopillar
slug: gopillar-eligibility
source_date: '2026-11-09'
source_filename: gopillar-eligibility.yml
source_heading: Eligibility
source_page: https://gopillar.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GoPillar\naid: gopillar\nurl: https://gopillar.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To register on the Portal, Users must be at least 18 years old.\n- type: business\n  text: Users who expect to use GoPillar’s service more than once may choose to convert their Client account into\n    a Business Client account by subscribing to the relevant monthly plan\n- type: developer\n  text: It may be activated by a User possessing the experience and professional qualifications required in architectural\n\
  \    design.\nrestricted_uses:\n- summary: Design Ideas are not final architectural solutions\n  text: GoPillar does not provide final/executive architectural solutions and is intended solely as a means of obtaining\n    general guidance on possible interior and/or exterior design solutions\n- summary: Prohibited Content types\n  text: is pornographic, obscene or child-pornographic;\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: GoPillar reserves the right to request an identity document to verify personal data.\nminimum_age:\n  value: '18'\n  text: To register on the Portal, Users must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/gopillar/eligibility/gopillar-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from GoPillar's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Architecture
- Interior Design
- Design Marketplace
- Crowdsourcing
- Construction
- Real Estate
- E-Learning
---
