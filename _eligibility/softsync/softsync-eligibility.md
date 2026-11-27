---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting these Terms on behalf of the legal entity, you represent and warrant that you have full authority to bind such entity to these terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: You agree not to export SoftSync from any country in violation of applicable legal restrictions on such export.
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
name: Scopic
provenance_date: '2026-11-10'
provider_name: Scopic
provider_slug: softsync
slug: softsync-eligibility
source_date: '2026-11-10'
source_filename: softsync-eligibility.yml
source_heading: Eligibility
source_page: https://softsync.io/privacy-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Scopic\naid: softsync\nurl: https://softsync.io/privacy-terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting these Terms on behalf of the legal entity, you represent and warrant that you have\n    full authority to bind such entity to these terms\nrestricted_uses:\n- summary: Export restrictions\n  text: You agree not to export SoftSync from any country in violation of applicable legal restrictions on such\n    export.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/softsync/eligibility/softsync-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Scopic's own page on 2026-11-10.
synthetic: false
tags:
- Integration
- Project Management
- Automation
- Jira
- Teamwork
---
