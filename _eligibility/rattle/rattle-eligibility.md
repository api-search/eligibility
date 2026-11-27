---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this TOS on behalf of a company, business or other legal entity, you represent that you have the authority to bind such entity and its affiliates to this TOS
    type: business
  minimum_age:
    text: you are eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: You may not remove or export from the United States or allow the export or re-export of the Services or anything related thereto, or any direct product thereof in violation of any restrictions, laws or regulations
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: As part of the registration process, you will identify an administrative user name and password for your account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rattle
provenance_date: '2026-11-10'
provider_name: Rattle
provider_slug: rattle
slug: rattle-eligibility
source_date: '2026-11-10'
source_filename: rattle-eligibility.yml
source_heading: Eligibility
source_page: https://www.gorattle.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rattle\naid: rattle\nurl: https://www.gorattle.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this TOS on behalf of a company, business or other legal entity, you represent\n    that you have the authority to bind such entity and its affiliates to this TOS\nrestricted_uses:\n- summary: Export restrictions\n  text: You may not remove or export from the United States or allow the export or re-export of the Services or\n    anything related thereto, or any direct product thereof in violation of any restrictions,\
  \ laws or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: As part of the registration process, you will identify an administrative user name and password for your\n    account\nminimum_age:\n  value: '18'\n  text: you are eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/rattle/eligibility/rattle-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Rattle's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sales
- Revenue Operations
- CRM
- Salesforce
- Slack
- Microsoft Teams
- Sales Automation
- Revenue Intelligence
- Workflow Automation
- Artificial Intelligence
---
