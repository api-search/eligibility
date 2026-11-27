---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are registering for our Platform on behalf of an organization, you warrant that you are authorized to agree to this Agreement on their behalf.
    type: business
  minimum_age:
    text: Our Platform are not intended for minors under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Minors
    text: Our Platform are not intended for minors under the age of 18.
  - summary: Children's personal information
    text: send us any personal information of children under 13 or the applicable age of digital consent
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
name: Kaiber
provenance_date: '2026-11-09'
provider_name: Kaiber
provider_slug: kaiber
slug: kaiber-eligibility
source_date: '2026-11-09'
source_filename: kaiber-eligibility.yml
source_heading: Eligibility
source_page: https://kaiber.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kaiber\naid: kaiber\nurl: https://kaiber.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are registering for our Platform on behalf of an organization, you warrant that you are authorized\n    to agree to this Agreement on their behalf.\nrestricted_uses:\n- summary: Minors\n  text: Our Platform are not intended for minors under the age of 18.\n- summary: Children's personal information\n  text: send us any personal information of children under 13 or the applicable age of digital consent\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our Platform are not intended for minors under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/kaiber/eligibility/kaiber-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Kaiber's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Generative AI
- Video
- Video Generation
- Creative Tools
- Media
---
