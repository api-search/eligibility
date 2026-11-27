---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are a consumer and not a business user
    type: individual
  - text: if you are a business user
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful activities
    text: engage in any activities through or in connection with this Site that seek to attempt to harm minors or are unlawful, offensive, obscene, threatening, harassing, abusive or that violate any right of any third party
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
name: Mimecast
provenance_date: '2026-11-10'
provider_name: Mimecast
provider_slug: mimecast
slug: mimecast-eligibility
source_date: '2026-11-10'
source_filename: mimecast-eligibility.yml
source_heading: Eligibility
source_page: https://www.mimecast.com/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mimecast\naid: mimecast\nurl: https://www.mimecast.com/legal/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: if you are a consumer and not a business user\n- type: business\n  text: if you are a business user\nrestricted_uses:\n- summary: Unlawful or harmful activities\n  text: engage in any activities through or in connection with this Site that seek to attempt to harm minors or\n    are unlawful, offensive, obscene, threatening, harassing, abusive or that violate any right of any third party\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mimecast/eligibility/mimecast-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Mimecast's own page on 2026-11-10.
synthetic: false
tags:
- Email Security
- Cloud
- Data Loss Prevention
- Threat Protection
- Collaboration
- Company
---
