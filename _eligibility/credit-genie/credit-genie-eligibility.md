---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you must 1) be a citizen or legal resident of the United States
  entity_types:
  - text: agree to only have one Credit Genie account, which must be in your real name
    type: individual
  minimum_age:
    text: be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Cash Boost state restrictions
    text: The CASH BOOST Service is not currently available to residents of Connecticut, Maryland, Nevada, Hawaii, Washington, D.C., or Wisconsin.
  - summary: Earn Services state restrictions
    text: The Earn Services are not available to residents of Connecticut, Maryland, Nevada, Hawaii, or Washington, D.C.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: In order to use certain Services, Credit Genie may verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Credit Genie
provenance_date: '2026-11-09'
provider_name: Credit Genie
provider_slug: credit-genie
slug: credit-genie-eligibility
source_date: '2026-11-09'
source_filename: credit-genie-eligibility.yml
source_heading: Eligibility
source_page: https://www.creditgenie.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Credit Genie\naid: credit-genie\nurl: https://www.creditgenie.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you must 1) be a citizen or legal resident of the United States\nentity_types:\n- type: individual\n  text: agree to only have one Credit Genie account, which must be in your real name\nrestricted_uses:\n- summary: Cash Boost state restrictions\n  text: The CASH BOOST Service is not currently available to residents of Connecticut, Maryland, Nevada, Hawaii,\n    Washington, D.C., or Wisconsin.\n- summary: Earn Services state\
  \ restrictions\n  text: The Earn Services are not available to residents of Connecticut, Maryland, Nevada, Hawaii, or Washington,\n    D.C.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: In order to use certain Services, Credit Genie may verify your identity.\nminimum_age:\n  value: '18'\n  text: be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/credit-genie/eligibility/credit-genie-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Credit Genie's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Consumer Finance
- Lending
- Cash Advance
- Personal Finance
- Mobile App
---
