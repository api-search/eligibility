---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Wrapbook makes no representations or warranties about the Platform’s uptime, availability, or permissibility in any particular geographical location.
  entity_types:
  - text: If User is a business entity, User will designate and authorize either itself and/or one or more individuals with authority to (i) act on User’s behalf
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Consumer privacy 'tester' access
    text: The Platform and Services are not intended to be accessed by any person who seeks or intends to access the Platform or Services for purposes of being a “tester” plaintiff or claimant
  - summary: Adult content
    text: Use the Services or Platform in connection with any adult content
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: User gives Wrapbook permission to obtain, verify, and record information that identifies the individual or entity who creates an Account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Wrapbook
provenance_date: '2026-11-10'
provider_name: Wrapbook
provider_slug: wrapbook
slug: wrapbook-eligibility
source_date: '2026-11-10'
source_filename: wrapbook-eligibility.yml
source_heading: Eligibility
source_page: https://www.wrapbook.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wrapbook\naid: wrapbook\nurl: https://www.wrapbook.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Wrapbook makes no representations or warranties about the Platform’s uptime, availability, or permissibility\n    in any particular geographical location.\nentity_types:\n- type: business\n  text: If User is a business entity, User will designate and authorize either itself and/or one or more individuals\n    with authority to (i) act on User’s behalf\nrestricted_uses:\n- summary: Consumer privacy 'tester' access\n  text: The Platform and\
  \ Services are not intended to be accessed by any person who seeks or intends to access the\n    Platform or Services for purposes of being a “tester” plaintiff or claimant\n- summary: Adult content\n  text: Use the Services or Platform in connection with any adult content\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: User gives Wrapbook permission to obtain, verify, and record information that identifies the individual\n    or entity who creates an Account\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wrapbook/eligibility/wrapbook-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Wrapbook's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Entertainment
- Payroll
- Production Accounting
- Accounts Payable
- Film
- Television
- Fintech
---
