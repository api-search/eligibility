---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract.
    type: individual
  - text: You agree to obtain and maintain appropriate insurance for you, your entity, and/or your Guide Service
    type: business
  minimum_age:
    text: You represent and warrant that you are an individual of legal age to form a binding contract.
    value: legal age
  restricted_uses:
  - summary: Prohibited service uses
    text: is dangerous, harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise objectionable
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
name: AnyCreek
provenance_date: '2026-11-09'
provider_name: AnyCreek
provider_slug: anycreek
slug: anycreek-eligibility
source_date: '2026-11-09'
source_filename: anycreek-eligibility.yml
source_heading: Eligibility
source_page: https://anycreek.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AnyCreek\naid: anycreek\nurl: https://anycreek.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract.\n- type: business\n  text: You agree to obtain and maintain appropriate insurance for you, your entity, and/or your Guide Service\nrestricted_uses:\n- summary: Prohibited service uses\n  text: is dangerous, harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise\n    objectionable\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: You represent and warrant that you are an individual of legal age to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/anycreek/eligibility/anycreek-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AnyCreek's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Calendar Management
- Guide Assignments
- Marketing
- SEO
- Outdoor Guides
- Outfitters
---
