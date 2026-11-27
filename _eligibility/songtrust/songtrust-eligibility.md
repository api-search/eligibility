---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are at least eighteen (18) years of age
    type: individual
  - text: entering into this agreement for the Services, registering and creating an Account and/or providing information to us on behalf of one or more other writers, a group, or a music publisher/administrator or other entity
    type: business
  minimum_age:
    text: You are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Non-Qualified Works may be declined
    text: Songtrust reserves the right to decline to administer (or to revoke administration of) any of the Compositions or other content you provide to us as part of the Services, for any reason
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You will also be required to provide a tax form, verified by Songtrust and/or its third-party payment processor(s)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Songtrust
provenance_date: '2026-11-10'
provider_name: Songtrust
provider_slug: songtrust
slug: songtrust-eligibility
source_date: '2026-11-10'
source_filename: songtrust-eligibility.yml
source_heading: Eligibility
source_page: https://app.songtrust.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Songtrust\naid: songtrust\nurl: https://app.songtrust.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are at least eighteen (18) years of age\n- type: business\n  text: entering into this agreement for the Services, registering and creating an Account and/or providing information\n    to us on behalf of one or more other writers, a group, or a music publisher/administrator or other entity\nrestricted_uses:\n- summary: Non-Qualified Works may be declined\n  text: Songtrust reserves the right to decline to administer\
  \ (or to revoke administration of) any of the Compositions\n    or other content you provide to us as part of the Services, for any reason\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You will also be required to provide a tax form, verified by Songtrust and/or its third-party payment processor(s)\nminimum_age:\n  value: '18'\n  text: You are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/songtrust/eligibility/songtrust-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Songtrust's own page on 2026-11-10.
synthetic: false
tags:
- Music Publishing
- Publishing Administration
- Royalty Collection
- Performance Royalties
- Mechanical Royalties
- Songwriters
- Composers
- Music Rights
- Copyright
- PRO
- Collection Societies
- Music Metadata
- Catalog Management
- Downtown Music
- Entertainment
---
