---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served:
    - US
    text: Online giving and related features are available only to organizations verified by DonorDock as IRS-recognized tax-exempt entities based in the United States. Comprehensive U.S. sanctions currently including Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk, and Luhansk regions of Ukraine.
  entity_types:
  - text: Except where noted below, the intended audience for the Service and this Privacy Policy are nonprofit organizations and their team members (“Users”)
    type: nonprofit
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal or emergency fundraising
    text: solicit or process funds for any individual's personal, medical, memorial, or emergency expenses
  verification:
    approval_required: null
    kyb: true
    kyc: null
    text: Online giving and related features are available only to organizations verified by DonorDock as IRS-recognized tax-exempt entities based in the United States.
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DonorDock
provenance_date: '2026-11-09'
provider_name: DonorDock
provider_slug: donordock
slug: donordock-eligibility
source_date: '2026-11-09'
source_filename: donordock-eligibility.yml
source_heading: Eligibility
source_page: https://www.donordock.com/terms-conditions-privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DonorDock\naid: donordock\nurl: https://www.donordock.com/terms-conditions-privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: Online giving and related features are available only to organizations verified by DonorDock as IRS-recognized\n    tax-exempt entities based in the United States. Comprehensive U.S. sanctions currently including Cuba, Iran,\n    North Korea, Syria, and the Crimea, Donetsk, and Luhansk regions of Ukraine.\nentity_types:\n- type: nonprofit\n  text: Except where noted below, the intended audience for the Service\
  \ and this Privacy Policy are nonprofit organizations\n    and their team members (“Users”)\nrestricted_uses:\n- summary: Personal or emergency fundraising\n  text: solicit or process funds for any individual's personal, medical, memorial, or emergency expenses\nverification:\n  kyc: null\n  kyb: true\n  approval_required: null\n  text: Online giving and related features are available only to organizations verified by DonorDock as IRS-recognized\n    tax-exempt entities based in the United States.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/donordock/eligibility/donordock-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from DonorDock's own page on 2026-11-09.
synthetic: false
tags:
- Non-Profit
- Software-as-a-Service
- Fundraising
- Donor Management
- Artificial Intelligence
---
