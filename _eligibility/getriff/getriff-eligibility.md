---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use this Website.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use this Website.
    value: '18'
  restricted_uses:
  - summary: Harmful, unlawful or abusive use
    text: in any way which is harmful, unlawful, illegal, abusive, harassing, threatening or otherwise objectionable or in breach of any applicable law, regulation, governmental order;
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
name: getriff
provenance_date: '2026-11-09'
provider_name: getriff
provider_slug: getriff
slug: getriff-eligibility
source_date: '2026-11-09'
source_filename: getriff-eligibility.yml
source_heading: Eligibility
source_page: https://getriff.co/documents/Website-terms-and-conditions.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: getriff\naid: getriff\nurl: https://getriff.co/documents/Website-terms-and-conditions.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use this Website.\nrestricted_uses:\n- summary: Harmful, unlawful or abusive use\n  text: in any way which is harmful, unlawful, illegal, abusive, harassing, threatening or otherwise objectionable\n    or in breach of any applicable law, regulation, governmental order;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: You must be at least 18 years of age to use this Website.\n"
source_yaml_url: https://artifacts.apis.io/getriff/eligibility/getriff-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from getriff's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video Conferencing
- Team Collaboration
- Remote Work
- Voice
- Productivity
- Desktop Software
---
