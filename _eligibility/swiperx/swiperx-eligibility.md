---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: For Users in Indonesia, if any of these updates result in substantial alteration to the Users’ rights, mClinica will notify the Users of the changes by pop-up notice
  entity_types:
  - text: The term User shall include any person who has registered an account on the App or Site, or has used the App or Site.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Drug advertising compliance
    text: Not advertise or promote any drugs in the App or Site in a manner which is non-compliant with applicable laws relating to the advertisements of drugs.
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
name: SwipeRx
provenance_date: '2026-11-10'
provider_name: SwipeRx
provider_slug: swiperx
slug: swiperx-eligibility
source_date: '2026-11-10'
source_filename: swiperx-eligibility.yml
source_heading: Eligibility
source_page: https://www.swiperx.com/user-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SwipeRx\naid: swiperx\nurl: https://www.swiperx.com/user-agreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: For Users in Indonesia, if any of these updates result in substantial alteration to the Users’ rights, mClinica\n    will notify the Users of the changes by pop-up notice\nentity_types:\n- type: individual\n  text: The term User shall include any person who has registered an account on the App or Site, or has used the\n    App or Site.\nrestricted_uses:\n- summary: Drug advertising compliance\n  text: Not advertise or promote any drugs in the App or Site in a manner\
  \ which is non-compliant with applicable\n    laws relating to the advertisements of drugs.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/swiperx/eligibility/swiperx-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from SwipeRx's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Pharmacy
- B2B Commerce
- E-Commerce
- Southeast Asia
- Marketplace
- Digital Health
- Mobile
---
