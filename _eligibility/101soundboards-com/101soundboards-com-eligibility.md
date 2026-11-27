---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Our Service does not address anyone under the age of 18 ("Children").
    value: '18'
  restricted_uses:
  - summary: TTS voice restrictions
    text: TTS voices are synthetic creations and do not imply any affiliation with the person whose name or likeness may be associated with it.
  - summary: Impersonation and deception
    text: You must not use the web site and its features for any type of impersonation, deception, slur, abuse, or mistreatment of any individual or group.
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
name: 101 Soundboards
provenance_date: '2026-11-09'
provider_name: 101 Soundboards
provider_slug: 101soundboards-com
slug: 101soundboards-com-eligibility
source_date: '2026-11-09'
source_filename: 101soundboards-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.101soundboards.com/pages/terms_and_privacy#terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 101 Soundboards\naid: 101soundboards-com\nurl: https://www.101soundboards.com/pages/terms_and_privacy#terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: TTS voice restrictions\n  text: TTS voices are synthetic creations and do not imply any affiliation with the person whose name or likeness\n    may be associated with it.\n- summary: Impersonation and deception\n  text: You must not use the web site and its features for any type of impersonation, deception, slur, abuse, or\n    mistreatment of any individual or group.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our Service does not address anyone under the age of 18 (\"Children\").\n"
source_yaml_url: https://artifacts.apis.io/101soundboards-com/eligibility/101soundboards-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from 101 Soundboards's own page on 2026-11-09.
synthetic: false
tags:
- Audio
- soundboard
- Free
- Text-to-Speech
- Community
---
