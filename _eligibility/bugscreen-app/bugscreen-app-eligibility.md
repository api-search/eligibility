---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to enter into a binding contract to use the Service.
    type: individual
  - text: you agree to be bound by these Terms on behalf of yourself and/or the legal entity you represent
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to enter into a binding contract to use the Service.
    value: '18'
  restricted_uses:
  - summary: Sensitive data uploads
    text: upload content that is unlawful, defamatory, harassing, or that contains payment card data, government-issued identifiers, or special-category personal data
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
name: BugScreen
provenance_date: '2026-11-09'
provider_name: BugScreen
provider_slug: bugscreen-app
slug: bugscreen-app-eligibility
source_date: '2026-11-09'
source_filename: bugscreen-app-eligibility.yml
source_heading: Eligibility
source_page: https://www.bugscreen.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BugScreen\naid: bugscreen-app\nurl: https://www.bugscreen.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter into a binding contract to use the Service.\n- type: business\n  text: you agree to be bound by these Terms on behalf of yourself and/or the legal entity you represent\nrestricted_uses:\n- summary: Sensitive data uploads\n  text: upload content that is unlawful, defamatory, harassing, or that contains payment card data, government-issued\n    identifiers, or special-category\
  \ personal data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to enter into a binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/bugscreen-app/eligibility/bugscreen-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from BugScreen's own page on 2026-11-09.
synthetic: false
tags:
- Bug Reporting
- QA
- Mobile
- SDK
- Integration
---
