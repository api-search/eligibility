---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of a company or other entity, you represent that you have authority to bind that entity, and these Terms apply to that entity.
    type: business
  minimum_age:
    text: You must be at least 16 years of age (or the age of digital consent in your country, if higher)
    value: '16'
  restricted_uses:
  - summary: Illegal activities
    text: Use the service for illegal activities
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
name: Bespree
provenance_date: '2026-11-09'
provider_name: Bespree
provider_slug: bespree-com
slug: bespree-com-eligibility
source_date: '2026-11-09'
source_filename: bespree-com-eligibility.yml
source_heading: Eligibility
source_page: https://bespree.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bespree\naid: bespree-com\nurl: https://bespree.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of a company or other entity, you represent that you have authority\n    to bind that entity, and these Terms apply to that entity.\nrestricted_uses:\n- summary: Illegal activities\n  text: Use the service for illegal activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years of age\
  \ (or the age of digital consent in your country, if higher)\n"
source_yaml_url: https://artifacts.apis.io/bespree-com/eligibility/bespree-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bespree's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Job Search
- Resume Builder
- CoverLetter
---
