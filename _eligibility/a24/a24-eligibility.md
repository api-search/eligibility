---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: all new members must list an address in the United States of America in order to receive a Membership.
  entity_types:
  - text: By making a purchase through the Service, you represent that you are at least the age of majority in your state/and or country of residence, as applicable.
    type: individual
  minimum_age:
    text: NO ONE UNDER THE AGE OF 13 IS PERMITTED TO USE OR ACCESS THE SERVICE OR CONTENT.
    value: '13'
  restricted_uses:
  - summary: Products for personal use only
    text: Products purchased through the Service may only be used for individual, personal use.
  - summary: Personal, non-commercial Content use
    text: for your own personal, non-commercial use only.
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
name: A24
provenance_date: '2026-11-09'
provider_name: A24
provider_slug: a24
slug: a24-eligibility
source_date: '2026-11-09'
source_filename: a24-eligibility.yml
source_heading: Eligibility
source_page: https://a24films.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: A24\naid: a24\nurl: https://a24films.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: all new members must list an address in the United States of America in order to receive a Membership.\nentity_types:\n- type: individual\n  text: By making a purchase through the Service, you represent that you are at least the age of majority in your\n    state/and or country of residence, as applicable.\nrestricted_uses:\n- summary: Products for personal use only\n  text: Products purchased through the Service may only be used for individual, personal use.\n\
  - summary: Personal, non-commercial Content use\n  text: for your own personal, non-commercial use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: NO ONE UNDER THE AGE OF 13 IS PERMITTED TO USE OR ACCESS THE SERVICE OR CONTENT.\n"
source_yaml_url: https://artifacts.apis.io/a24/eligibility/a24-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from A24's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Media
- Film
- Television
- Entertainment
- Streaming
- Merchandise
---
