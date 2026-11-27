---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using our Services on behalf of a business, that business accepts these terms.
    type: business
  - text: You affirm that you are 13 years of age or older, and competent to enter into the terms, conditions, obligations, affirmations, representations, and warranties set forth in these Terms of Service
    type: individual
  minimum_age:
    text: You affirm that you are 13 years of age or older
    value: '13'
  restricted_uses:
  - summary: Dangerous content
    text: Dangerous content that we consider to encourage injurious or illegal activities
  - summary: Hateful content
    text: Hateful content that promotes or encourages hate, violence, or discrimination against a person or group
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
name: WebComics
provenance_date: '2026-11-10'
provider_name: WebComics
provider_slug: webcomicsapp
slug: webcomicsapp-eligibility
source_date: '2026-11-10'
source_filename: webcomicsapp-eligibility.yml
source_heading: Eligibility
source_page: https://webcomicsapp.com/en/server/service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WebComics\naid: webcomicsapp\nurl: https://webcomicsapp.com/en/server/service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using our Services on behalf of a business, that business accepts these terms.\n- type: individual\n  text: You affirm that you are 13 years of age or older, and competent to enter into the terms, conditions, obligations,\n    affirmations, representations, and warranties set forth in these Terms of Service\nrestricted_uses:\n- summary: Dangerous content\n  text: Dangerous content that we consider to\
  \ encourage injurious or illegal activities\n- summary: Hateful content\n  text: Hateful content that promotes or encourages hate, violence, or discrimination against a person or group\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You affirm that you are 13 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/webcomicsapp/eligibility/webcomicsapp-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from WebComics's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Comics
- Manga
- Manhwa
- Manhua
- Entertainment
- Reading
- Mobile App
---
