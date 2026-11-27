---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By creating an account you accept these Terms on behalf of yourself and any organisation you represent.
    type: business
  minimum_age:
    text: You must be at least 16 years old and capable of entering into a binding contract under the law of your jurisdiction.
    value: '16'
  restricted_uses:
  - summary: Unlawful regulated promotions
    text: Promote regulated industries (firearms, illicit drugs, MLM schemes, gambling without licence) in jurisdictions where doing so is unlawful.
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
name: send16-com
provenance_date: '2026-11-10'
provider_name: send16-com
provider_slug: send16-com
slug: send16-com-eligibility
source_date: '2026-11-10'
source_filename: send16-com-eligibility.yml
source_heading: Eligibility
source_page: https://send16.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: send16-com\naid: send16-com\nurl: https://send16.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: By creating an account you accept these Terms on behalf of yourself and any organisation you represent.\nrestricted_uses:\n- summary: Unlawful regulated promotions\n  text: Promote regulated industries (firearms, illicit drugs, MLM schemes, gambling without licence) in jurisdictions\n    where doing so is unlawful.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text:\
  \ You must be at least 16 years old and capable of entering into a binding contract under the law of your\n    jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/send16-com/eligibility/send16-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from send16-com's own page on 2026-11-10.
synthetic: false
tags:
- Email
- Marketing
- Automation
- Artificial Intelligence
- Software-as-a-Service
---
