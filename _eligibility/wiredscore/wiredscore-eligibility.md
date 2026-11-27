---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you open a WiredScore account on behalf of a company, organization, or other entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use
    text: in compliance with this Agreement and all applicable local, state, national, and international laws, rules and regulations
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: WiredScore does not have any obligation to verify the identity of the users subscribing to our site
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: WiredScore
provenance_date: '2026-11-10'
provider_name: WiredScore
provider_slug: wiredscore
slug: wiredscore-eligibility
source_date: '2026-11-10'
source_filename: wiredscore-eligibility.yml
source_heading: Eligibility
source_page: https://wiredscore.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WiredScore\naid: wiredscore\nurl: https://wiredscore.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you open a WiredScore account on behalf of a company, organization, or other entity\nrestricted_uses:\n- summary: Unlawful use\n  text: in compliance with this Agreement and all applicable local, state, national, and international laws, rules\n    and regulations\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: WiredScore does not have any obligation to verify the identity of the users\
  \ subscribing to our site\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wiredscore/eligibility/wiredscore-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from WiredScore's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Vertical Software
- Real Estate
- PropTech
- Building Certification
- Smart Buildings
- Digital Connectivity
- Sustainability
---
