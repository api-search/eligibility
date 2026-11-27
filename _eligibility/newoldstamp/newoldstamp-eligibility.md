---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you represent the other person or you are acting on behalf of your company - you are authorized to do so;
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: you will use the Services for lawful purposes only and subject to these Terms;
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
name: Newoldstamp
provenance_date: '2026-11-10'
provider_name: Newoldstamp
provider_slug: newoldstamp
slug: newoldstamp-eligibility
source_date: '2026-11-10'
source_filename: newoldstamp-eligibility.yml
source_heading: Eligibility
source_page: https://newoldstamp.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Newoldstamp\naid: newoldstamp\nurl: https://newoldstamp.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if you represent the other person or you are acting on behalf of your company - you are authorized to do\n    so;\nrestricted_uses:\n- summary: Lawful purposes only\n  text: you will use the Services for lawful purposes only and subject to these Terms;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/newoldstamp/eligibility/newoldstamp-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Newoldstamp's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Email Signatures
- Email Signature Management
- Email Marketing
- Branding
- Software-as-a-Service
- Productivity
- Website Visitor Identification
- GraphQL
---
