---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services may not be used by anyone under the age of 18 without the supervision of a parent or legal guardian who agrees to be bound by these Terms.
    type: individual
  minimum_age:
    text: You represent and warrant that you are at least 18 years of age (or the age of legal majority under applicable law)
    value: '18'
  restricted_uses:
  - summary: Harassment and unlawful conduct
    text: Engage in any discriminatory, defamatory, libelous, hateful, harassing, abusive, obscene, threatening, physically dangerous, unlawful, or otherwise objectionable conduct
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
name: Nintendo
provenance_date: '2026-11-10'
provider_name: Nintendo
provider_slug: nintendo
slug: nintendo-eligibility
source_date: '2026-11-10'
source_filename: nintendo-eligibility.yml
source_heading: Eligibility
source_page: https://www.nintendo.com/us/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nintendo\naid: nintendo\nurl: https://www.nintendo.com/us/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services may not be used by anyone under the age of 18 without the supervision of a parent or legal\n    guardian who agrees to be bound by these Terms.\nrestricted_uses:\n- summary: Harassment and unlawful conduct\n  text: Engage in any discriminatory, defamatory, libelous, hateful, harassing, abusive, obscene, threatening, physically\n    dangerous, unlawful, or otherwise objectionable conduct\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least 18 years of age (or the age of legal majority under applicable\n    law)\n"
source_yaml_url: https://artifacts.apis.io/nintendo/eligibility/nintendo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Nintendo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Gaming
- Electronics
- Entertainment
- Japan
---
