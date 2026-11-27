---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are only to be availed by a Guest or Registered Client in a jurisdiction where it may be lawful to offer such Services.
  minimum_age:
    text: You hereby represent and warrant that you are of the age of majority and are legally capable of entering and executing this Agreement.
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: you will utilize said account(s) solely for lawful purposes and will remain aware of, and fully comply with, all applicable laws
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Registration by submitting a physical application form and other documentary proof is required for this user category.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Jiraaf
provenance_date: '2026-11-09'
provider_name: Jiraaf
provider_slug: jiraaf
slug: jiraaf-eligibility
source_date: '2026-11-09'
source_filename: jiraaf-eligibility.yml
source_heading: Eligibility
source_page: https://www.jiraaf.com/terms-and-condition
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jiraaf\naid: jiraaf\nurl: https://www.jiraaf.com/terms-and-condition\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are only to be availed by a Guest or Registered Client in a jurisdiction where it may be lawful\n    to offer such Services.\nentity_types: []\nrestricted_uses:\n- summary: Lawful purposes only\n  text: you will utilize said account(s) solely for lawful purposes and will remain aware of, and fully comply with,\n    all applicable laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Registration by submitting a physical application\
  \ form and other documentary proof is required for this\n    user category.\nminimum_age:\n  value: null\n  text: You hereby represent and warrant that you are of the age of majority and are legally capable of entering\n    and executing this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/jiraaf/eligibility/jiraaf-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Jiraaf's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Bonds
- Fixed Income
- Investing
- Wealth Management
- India
---
