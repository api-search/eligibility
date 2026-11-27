---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are at least the age of majority in the jurisdiction from which you access the Site and have the legal capacity to enter into these Terms & Conditions.
    type: individual
  - text: If you are accessing or using the Site on behalf of a company or other legal entity, you represent and warrant that you have authority to bind that entity to these Terms & Conditions
    type: business
  minimum_age:
    text: you are at least the age of majority in the jurisdiction from which you access the Site
    value: age of majority
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
name: CallMiner
provenance_date: '2026-11-09'
provider_name: CallMiner
provider_slug: callminer
slug: callminer-eligibility
source_date: '2026-11-09'
source_filename: callminer-eligibility.yml
source_heading: Eligibility
source_page: https://callminer.com/terms-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CallMiner\naid: callminer\nurl: https://callminer.com/terms-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least the age of majority in the jurisdiction from which you access\n    the Site and have the legal capacity to enter into these Terms & Conditions.\n- type: business\n  text: If you are accessing or using the Site on behalf of a company or other legal entity, you represent and warrant\n    that you have authority to bind that entity to these Terms & Conditions\nrestricted_uses:\
  \ []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you are at least the age of majority in the jurisdiction from which you access the Site\n"
source_yaml_url: https://artifacts.apis.io/callminer/eligibility/callminer-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from CallMiner's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Conversation Intelligence
- Speech Analytics
- Contact Center
- Customer Experience
- Artificial Intelligence
- Analytics
- Transcription
- Quality Management
- Compliance
---
