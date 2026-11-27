---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of an organisation, you warrant that you are authorised to bind that organisation to these Terms.
    type: business
  minimum_age:
    text: You must be at least 16 years old to use the Service.
    value: '16'
  restricted_uses:
  - summary: Objectionable content
    text: Objectionable content includes sexual content involving minors, explicit sexual content in a book not marked for adults, hate speech, harassment or bullying
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
name: Anthra
provenance_date: '2026-11-09'
provider_name: Anthra
provider_slug: anthra-com
slug: anthra-com-eligibility
source_date: '2026-11-09'
source_filename: anthra-com-eligibility.yml
source_heading: Eligibility
source_page: https://anthra.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anthra\naid: anthra-com\nurl: https://anthra.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of an organisation, you warrant that you are authorised to bind that organisation\n    to these Terms.\nrestricted_uses:\n- summary: Objectionable content\n  text: Objectionable content includes sexual content involving minors, explicit sexual content in a book not marked\n    for adults, hate speech, harassment or bullying\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/anthra-com/eligibility/anthra-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Anthra's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- BookCreation
- Writing
- Illustration
- Audiobook
---
