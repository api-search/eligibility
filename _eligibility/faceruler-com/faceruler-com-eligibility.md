---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No harassment or judging people
    text: Do not use FaceRuler to harass, bully, or "mog" others — measurement is information, not ammunition.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Sign-in (optional, for purchases) uses Google OAuth; see the privacy policy for what is stored.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: FaceRuler
provenance_date: '2026-11-09'
provider_name: FaceRuler
provider_slug: faceruler-com
slug: faceruler-com-eligibility
source_date: '2026-11-09'
source_filename: faceruler-com-eligibility.yml
source_heading: Eligibility
source_page: https://faceruler.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FaceRuler\naid: faceruler-com\nurl: https://faceruler.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No harassment or judging people\n  text: Do not use FaceRuler to harass, bully, or \"mog\" others — measurement is information, not ammunition.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Sign-in (optional, for purchases) uses Google OAuth; see the privacy policy for what is stored.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/faceruler-com/eligibility/faceruler-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from FaceRuler's own page on 2026-11-09.
synthetic: false
tags:
- Face Rating
- Attractiveness
- Artificial Intelligence
- Privacy
- Free
---
