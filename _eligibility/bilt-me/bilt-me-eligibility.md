---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not access or use the Services (i) from jurisdictions subject to comprehensive sanctions imposed by the European Union or the United States
  entity_types:
  - text: if you are using the Site or the Services as a natural person on your own behalf, you are at least 18 years old or you have the consent from your legal guardian to accept these Terms
    type: individual
  - text: if you are using the Site or the Services on behalf of a legal entity, you warrant that you are authorised to accept these Terms on that legal entity’s behalf
    type: business
  minimum_age:
    text: you are at least 18 years old or you have the consent from your legal guardian to accept these Terms
    value: '18'
  restricted_uses:
  - summary: Output not professional advice
    text: In no way does the Output constitute legal, medical, financial, or other professional advice, and it must not be used as or relied upon as such.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must create an account (“User Account”) at https://app.bilt.me/sign-up to access certain features of the Site or the Services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bilt
provenance_date: '2026-11-09'
provider_name: Bilt
provider_slug: bilt-me
slug: bilt-me-eligibility
source_date: '2026-11-09'
source_filename: bilt-me-eligibility.yml
source_heading: Eligibility
source_page: https://bilt.me/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bilt\naid: bilt-me\nurl: https://bilt.me/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not access or use the Services (i) from jurisdictions subject to comprehensive sanctions imposed\n    by the European Union or the United States\nentity_types:\n- type: individual\n  text: if you are using the Site or the Services as a natural person on your own behalf, you are at least 18 years\n    old or you have the consent from your legal guardian to accept these Terms\n- type: business\n  text: if you are using the Site or the Services on behalf of a legal entity, you warrant\
  \ that you are authorised\n    to accept these Terms on that legal entity’s behalf\nrestricted_uses:\n- summary: Output not professional advice\n  text: In no way does the Output constitute legal, medical, financial, or other professional advice, and it must\n    not be used as or relied upon as such.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must create an account (“User Account”) at https://app.bilt.me/sign-up to access certain features of\n    the Site or the Services\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old or you have the consent from your legal guardian to accept these Terms\n"
source_yaml_url: https://artifacts.apis.io/bilt-me/eligibility/bilt-me-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Bilt's own page on 2026-11-09.
synthetic: false
tags:
- Mobile
- Artificial Intelligence
- No-Code
- App Builder
- Estonia
---
