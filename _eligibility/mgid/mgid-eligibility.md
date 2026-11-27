---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: shall mean the entity accepting the Agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Adult, defamatory, hateful or illegal content
    text: the display of adult, obscene, profane, pornographic, defamatory, libelous, abusive, or illegal content
  - summary: Firearms, terrorism, illegal drugs
    text: the sale of firearms, the promotion of terrorism, the sale of illegal drugs, infringement of any minor’s rights, and the promotion of criminal activities
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
name: MGID
provenance_date: '2026-11-10'
provider_name: MGID
provider_slug: mgid
slug: mgid-eligibility
source_date: '2026-11-10'
source_filename: mgid-eligibility.yml
source_heading: Eligibility
source_page: https://www.mgid.com/services/advertisers-tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MGID\naid: mgid\nurl: https://www.mgid.com/services/advertisers-tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: shall mean the entity accepting the Agreement\nrestricted_uses:\n- summary: Adult, defamatory, hateful or illegal content\n  text: the display of adult, obscene, profane, pornographic, defamatory, libelous, abusive, or illegal content\n- summary: Firearms, terrorism, illegal drugs\n  text: the sale of firearms, the promotion of terrorism, the sale of illegal drugs, infringement of any minor’s\n    rights,\
  \ and the promotion of criminal activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mgid/eligibility/mgid-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from MGID's own page on 2026-11-10.
synthetic: false
tags:
- Native Advertising
- AdTech
- Publishers
- Advertisers
- Campaigns
- Content Monetization
- Programmatic
---
