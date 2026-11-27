---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a resident of the state of New Jersey or otherwise subject to the laws of the state of New Jersey
    type: individual
  minimum_age:
    text: the person submitting information to Easel is 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Unlawful, abusive or deceptive uses
    text: 'You may not use the Website or Service for any purpose that: is unlawful, threatening, abusive, harassing, defamatory, libelous, deceptive, fraudulent'
  - summary: Unsolicited advertising and spam
    text: constitutes unauthorized or unsolicited advertising, junk or bulk e-mail (also known as "spamming")
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
name: Easel
provenance_date: '2026-11-09'
provider_name: Easel
provider_slug: easel-com
slug: easel-com-eligibility
source_date: '2026-11-09'
source_filename: easel-com-eligibility.yml
source_heading: Eligibility
source_page: https://easel.com/pages/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Easel\naid: easel-com\nurl: https://easel.com/pages/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a resident of the state of New Jersey or otherwise subject to the laws of the state of New Jersey\nrestricted_uses:\n- summary: Unlawful, abusive or deceptive uses\n  text: 'You may not use the Website or Service for any purpose that: is unlawful, threatening, abusive, harassing,\n    defamatory, libelous, deceptive, fraudulent'\n- summary: Unsolicited advertising and spam\n  text: constitutes unauthorized\
  \ or unsolicited advertising, junk or bulk e-mail (also known as \"spamming\")\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: the person submitting information to Easel is 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/easel-com/eligibility/easel-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Easel's own page on 2026-11-09.
synthetic: false
tags:
- CNC
- Manufacturing
- Design
- Software
- Maker
---
