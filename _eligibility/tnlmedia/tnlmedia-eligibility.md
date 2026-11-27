---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any individual can obtain membership to the Services by completing the registration process.
    type: individual
  - text: If you are authorized by a company, incorporated organization, or any other legal entity to register for membership
    type: business
  minimum_age:
    text: If you are legally a minor, you should not register as a member until you have your legal representative or guardian read, understand, and consent to all the Terms
    value: null
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
name: TNL Mediagene
provenance_date: '2026-11-10'
provider_name: TNL Mediagene
provider_slug: tnlmedia
slug: tnlmedia-eligibility
source_date: '2026-11-10'
source_filename: tnlmedia-eligibility.yml
source_heading: Eligibility
source_page: https://www.tnlmediagene.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TNL Mediagene\naid: tnlmedia\nurl: https://www.tnlmediagene.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Any individual can obtain membership to the Services by completing the registration process.\n- type: business\n  text: If you are authorized by a company, incorporated organization, or any other legal entity to register for\n    membership\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: If you are legally a minor, you should\
  \ not register as a member until you have your legal representative\n    or guardian read, understand, and consent to all the Terms\n"
source_yaml_url: https://artifacts.apis.io/tnlmedia/eligibility/tnlmedia-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from TNL Mediagene's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Media
- Publishing
- Advertising
- AdTech
- Marketing
- Digital Media
- Content
- Analytics
- E-Commerce
- Header Bidding
- Programmatic
- Prebid
---
