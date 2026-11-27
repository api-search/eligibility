---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Prezi Services are not available to persons who are not legally eligible to be bound by this Agreement.
  entity_types:
  - text: If you register on behalf of a legal person, you represent to Prezi that you have the authority to bind that legal person and that your acceptance of this Agreement will be treated as acceptance by that legal person.
    type: business
  minimum_age:
    text: You may not use the Service if you are under 13 years of age.
    value: '13'
  restricted_uses:
  - summary: High-risk activities
    text: the Prezi Services are not designed or intended for use during high-risk activities.
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
name: Prezi
provenance_date: '2026-11-10'
provider_name: Prezi
provider_slug: prezi
slug: prezi-eligibility
source_date: '2026-11-10'
source_filename: prezi-eligibility.yml
source_heading: Eligibility
source_page: https://prezi.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prezi\naid: prezi\nurl: https://prezi.com/legal/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Prezi Services are not available to persons who are not legally eligible to be bound by this Agreement.\nentity_types:\n- type: business\n  text: If you register on behalf of a legal person, you represent to Prezi that you have the authority to bind\n    that legal person and that your acceptance of this Agreement will be treated as acceptance by that legal person.\nrestricted_uses:\n- summary: High-risk activities\n  text: the Prezi Services are not designed or intended\
  \ for use during high-risk activities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You may not use the Service if you are under 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/prezi/eligibility/prezi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Prezi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Presentations
- Productivity
- Software-as-a-Service
- Content Creation
- Design
- Video
---
