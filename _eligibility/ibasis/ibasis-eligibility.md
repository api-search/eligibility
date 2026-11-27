---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If User is using the iBASIS Site or Services on behalf of User’s employer, User represents that it is authorized to accept these Terms on its employer’s behalf.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or prohibited content
    text: User agrees that use of the site is subject to all applicable national, state, and local laws and regulations
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
name: iBasis
provenance_date: '2026-11-09'
provider_name: iBasis
provider_slug: ibasis
slug: ibasis-eligibility
source_date: '2026-11-09'
source_filename: ibasis-eligibility.yml
source_heading: Eligibility
source_page: https://ibasis.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: iBasis\naid: ibasis\nurl: https://ibasis.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If User is using the iBASIS Site or Services on behalf of User’s employer, User represents that it is authorized\n    to accept these Terms on its employer’s behalf.\nrestricted_uses:\n- summary: Unlawful or prohibited content\n  text: User agrees that use of the site is subject to all applicable national, state, and local laws and regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ibasis/eligibility/ibasis-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from iBasis's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Telecom Infrastructure
- Voice
- Messaging
- IoT
- eSIM
- Roaming
- Connectivity
- MVNO
---
