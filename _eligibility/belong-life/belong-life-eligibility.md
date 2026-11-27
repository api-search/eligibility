---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Service only if you are at least eighteen (18) years old.
    type: individual
  - text: If you use the Services on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind that other legal entity to these Terms.
    type: business
  minimum_age:
    text: You may use the Service only if you are at least eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: No emergency support
    text: THE SERVICE IS NOT INTENDED TO OFFER ANY SUPPORT OR SERVICES IN THE EVENT OF AN EMERGENCY.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We reserve the right to require you at any stage to provide proof of age
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Belong.Life
provenance_date: '2026-11-09'
provider_name: Belong.Life
provider_slug: belong-life
slug: belong-life-eligibility
source_date: '2026-11-09'
source_filename: belong-life-eligibility.yml
source_heading: Eligibility
source_page: https://belong.life/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Belong.Life\naid: belong-life\nurl: https://belong.life/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Service only if you are at least eighteen (18) years old.\n- type: business\n  text: If you use the Services on behalf of a company or other legal entity, you represent and warrant that you\n    have the authority to bind that other legal entity to these Terms.\nrestricted_uses:\n- summary: No emergency support\n  text: THE SERVICE IS NOT INTENDED TO OFFER ANY SUPPORT OR SERVICES\
  \ IN THE EVENT OF AN EMERGENCY.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We reserve the right to require you at any stage to provide proof of age\nminimum_age:\n  value: '18'\n  text: You may use the Service only if you are at least eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/belong-life/eligibility/belong-life-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Belong.Life's own page on 2026-11-09.
synthetic: false
tags:
- Health
- Artificial Intelligence
- Patient Engagement
- Digital Health
- Company
---
