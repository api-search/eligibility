---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: Our products and services and those of other companies described on our Online Services are available only where they are allowed to be offered within Canada.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Misuse of online services
    text: 'You agree you won''t directly or indirectly misuse our Online Services in any way, including by: Probing, scanning, or testing the vulnerability of any system or associated network.'
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
name: Canada Life
provenance_date: '2026-11-09'
provider_name: Canada Life
provider_slug: canada-life
slug: canada-life-eligibility
source_date: '2026-11-09'
source_filename: canada-life-eligibility.yml
source_heading: Eligibility
source_page: https://www.canadalife.com/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Canada Life\naid: canada-life\nurl: https://www.canadalife.com/terms-of-use.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: Our products and services and those of other companies described on our Online Services are available only\n    where they are allowed to be offered within Canada.\nentity_types: []\nrestricted_uses:\n- summary: Misuse of online services\n  text: 'You agree you won''t directly or indirectly misuse our Online Services in any way, including by: Probing,\n    scanning, or testing the vulnerability of any system or associated network.'\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/canada-life/eligibility/canada-life-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Canada Life's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Canada
- Life Insurance
- Health Insurance
- Employee Benefits
- Group Retirement
- Carrier
- ACORD
---
