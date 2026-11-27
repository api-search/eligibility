---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent and warrant that you are at least 18 years old and meet the minimum age of legal consent applicable in your jurisdiction
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: you represent and warrant that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No infringement
    text: You agree not to use the Services to infringe or attempt to infringe upon the intellectual property rights of others
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
name: Showrunner
provenance_date: '2026-11-10'
provider_name: Showrunner
provider_slug: showrunner
slug: showrunner-eligibility
source_date: '2026-11-10'
source_filename: showrunner-eligibility.yml
source_heading: Eligibility
source_page: https://www.showrunnerstudio.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Showrunner\naid: showrunner\nurl: https://www.showrunnerstudio.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you represent and warrant that you are at least 18 years old and meet the minimum age of legal consent applicable\n    in your jurisdiction\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority to bind you to these Terms\nrestricted_uses:\n- summary: No infringement\n  text: You agree not\
  \ to use the Services to infringe or attempt to infringe upon the intellectual property rights\n    of others\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/showrunner/eligibility/showrunner-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Showrunner's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Generative AI
- Animation
- Entertainment
- Media
- Streaming
---
