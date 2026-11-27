---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you're using our Services for an organization, you're agreeing to the terms of this Agreement on behalf of that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Samples not for AI development
    text: use any Sample for the purpose of training machine learning models, or for any form of Artificial Intelligence (AI) development
  - summary: Domain use lawfulness
    text: You may not use it for phishing, malware, spam, fraud, infringement or other abuse.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: you authorize us to use the identity verification you complete with LANDR to satisfy that requirement
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: LANDR
provenance_date: '2026-11-09'
provider_name: LANDR
provider_slug: landr
slug: landr-eligibility
source_date: '2026-11-09'
source_filename: landr-eligibility.yml
source_heading: Eligibility
source_page: https://www.landr.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LANDR\naid: landr\nurl: https://www.landr.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you're using our Services for an organization, you're agreeing to the terms of this Agreement on behalf\n    of that organization.\nrestricted_uses:\n- summary: Samples not for AI development\n  text: use any Sample for the purpose of training machine learning models, or for any form of Artificial Intelligence\n    (AI) development\n- summary: Domain use lawfulness\n  text: You may not use it for phishing,\
  \ malware, spam, fraud, infringement or other abuse.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: you authorize us to use the identity verification you complete with LANDR to satisfy that requirement\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/landr/eligibility/landr-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from LANDR's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Music
- Artificial Intelligence
- Audio
- Distribution
---
