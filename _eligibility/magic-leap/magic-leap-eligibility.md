---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an individual using the Site on behalf of an entity, you represent and warrant that you have the legal authority to bind such entity to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years of age or older to access, use or register for an account on the Sites.
    value: '18'
  restricted_uses:
  - summary: No sensitive regulated data in interactive features
    text: You may not use interactive features of our Sites to create, receive, maintain or transmit data that is sensitive or regulated
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
name: Magic Leap
provenance_date: '2026-11-10'
provider_name: Magic Leap
provider_slug: magic-leap
slug: magic-leap-eligibility
source_date: '2026-11-10'
source_filename: magic-leap-eligibility.yml
source_heading: Eligibility
source_page: https://www.magicleap.com/legal/website-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Magic Leap\naid: magic-leap\nurl: https://www.magicleap.com/legal/website-terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are an individual using the Site on behalf of an entity, you represent and warrant that you have\n    the legal authority to bind such entity to these Terms\nrestricted_uses:\n- summary: No sensitive regulated data in interactive features\n  text: You may not use interactive features of our Sites to create, receive, maintain or transmit data that is\n    sensitive or regulated\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age or older to access, use or register for an account on the Sites.\n"
source_yaml_url: https://artifacts.apis.io/magic-leap/eligibility/magic-leap-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Magic Leap's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Augmented Reality
- Spatial Computing
- AR Headset
- Developer Platform
- SDK
- OpenXR
- Unity
---
