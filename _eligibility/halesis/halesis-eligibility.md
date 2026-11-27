---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not be prohibited from using the Services under applicable sanctions, export controls, or other legal restrictions.
  entity_types:
  - text: 'You may use the Services only if: you are legally capable of entering into a binding agreement'
    type: individual
  - text: If you use the Services on behalf of an organisation, company, government entity, educational institution, or other legal entity, you represent and warrant that you have authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Decisions with significant consequences
    text: You must not rely on Outputs as the sole basis for decisions that could reasonably result in significant legal, financial, medical, employment, housing, educational, safety, or other material consequences for an individual.
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
name: Halesis
provenance_date: '2026-11-09'
provider_name: Halesis
provider_slug: halesis
slug: halesis-eligibility
source_date: '2026-11-09'
source_filename: halesis-eligibility.yml
source_heading: Eligibility
source_page: https://halesis.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Halesis\naid: halesis\nurl: https://halesis.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not be prohibited from using the Services under applicable sanctions, export controls, or other\n    legal restrictions.\nentity_types:\n- type: individual\n  text: 'You may use the Services only if: you are legally capable of entering into a binding agreement'\n- type: business\n  text: If you use the Services on behalf of an organisation, company, government entity, educational institution,\n    or other legal entity, you represent and warrant that you have authority\
  \ to bind that entity to these Terms.\nrestricted_uses:\n- summary: Decisions with significant consequences\n  text: You must not rely on Outputs as the sole basis for decisions that could reasonably result in significant\n    legal, financial, medical, employment, housing, educational, safety, or other material consequences for an individual.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/halesis/eligibility/halesis-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Halesis's own page on 2026-11-09.
synthetic: false
tags:
- Language Model Platform
- Developers
- AI Integration
- Chat Completions
---
