---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use our Services.
    type: individual
  - text: If you are using the Services on behalf of an entity, organization, or company, you represent and warrant that you have the authority to bind that entity, organization, or company to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use our Services.
    value: '18'
  restricted_uses:
  - summary: Unlawful or infringing user content
    text: 'You may not create, post, store, or share any User Content that: i) is libelous, defamatory, harassing, fraudulent, or otherwise unlawful'
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
name: Workrise
provenance_date: '2026-11-10'
provider_name: Workrise
provider_slug: workrise
slug: workrise-eligibility
source_date: '2026-11-10'
source_filename: workrise-eligibility.yml
source_heading: Eligibility
source_page: https://www.rigup.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Workrise\naid: workrise\nurl: https://www.rigup.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use our Services.\n- type: business\n  text: If you are using the Services on behalf of an entity, organization, or company, you represent and warrant\n    that you have the authority to bind that entity, organization, or company to these Terms\nrestricted_uses:\n- summary: Unlawful or infringing user content\n  text: 'You may not create, post, store, or share any User\
  \ Content that: i) is libelous, defamatory, harassing,\n    fraudulent, or otherwise unlawful'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/workrise/eligibility/workrise-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Workrise's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Energy
- Oil and Gas
- Workforce Management
- Vendor Management
- Procurement
- Source-to-Pay
- Workforce
- Software-as-a-Service
---
