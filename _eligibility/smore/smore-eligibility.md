---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting these Terms and using the Website and/or Services on behalf of a child, company, organization, government, or other legal entity, you represent and warrant that you are authorized to do so.
    type: business
  minimum_age:
    text: If you are a minor, you cannot accept these Terms and/or use the Services without approval from a parent or legal guardian.
    value: null
  restricted_uses:
  - summary: Educator-only license
    text: The Smore annual Educator account is only licensed for use by teachers, professors, or other educators and by their students under the educator’s direct supervision
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
name: Smore
provenance_date: '2026-11-10'
provider_name: Smore
provider_slug: smore
slug: smore-eligibility
source_date: '2026-11-10'
source_filename: smore-eligibility.yml
source_heading: Eligibility
source_page: https://www.smore.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Smore\naid: smore\nurl: https://www.smore.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting these Terms and using the Website and/or Services on behalf of a child, company, organization,\n    government, or other legal entity, you represent and warrant that you are authorized to do so.\nrestricted_uses:\n- summary: Educator-only license\n  text: The Smore annual Educator account is only licensed for use by teachers, professors, or other educators and\n    by their students under the educator’s direct supervision\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: If you are a minor, you cannot accept these Terms and/or use the Services without approval from a parent\n    or legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/smore/eligibility/smore-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Smore's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- EdTech
- Newsletters
- Communications
- Family Engagement
- Schools
- Content Creation
---
