---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - KE
    text: The Services offered by the Bank can only be utilized by persons over the age of 18 and are legally resident in Kenya.
  entity_types:
  - text: The Services offered by the Bank can only be utilized by persons over the age of 18
    type: individual
  minimum_age:
    text: over the age of 18
    value: '18'
  restricted_uses:
  - summary: Domestic and private use only
    text: We only supply the App for domestic and private use.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: Your application to open a Branch Account is dependent on the Bank’s verification of your identity, status and any other applicable information
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Branch International
provenance_date: '2026-11-09'
provider_name: Branch International
provider_slug: branch-international
slug: branch-international-eligibility
source_date: '2026-11-09'
source_filename: branch-international-eligibility.yml
source_heading: Eligibility
source_page: https://branch.co/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Branch International\naid: branch-international\nurl: https://branch.co/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - KE\n  excluded: []\n  text: The Services offered by the Bank can only be utilized by persons over the age of 18 and are legally resident\n    in Kenya.\nentity_types:\n- type: individual\n  text: The Services offered by the Bank can only be utilized by persons over the age of 18\nrestricted_uses:\n- summary: Domestic and private use only\n  text: We only supply the App for domestic and private use.\nverification:\n  kyc: true\n  kyb: null\n  approval_required:\
  \ true\n  text: Your application to open a Branch Account is dependent on the Bank’s verification of your identity, status\n    and any other applicable information\nminimum_age:\n  value: '18'\n  text: over the age of 18\n"
source_yaml_url: https://artifacts.apis.io/branch-international/eligibility/branch-international-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Branch International's own page on 2026-11-09.
synthetic: false
tags:
- Digital Banking
- Loans
- Payments
- Investment
- Savings
- Emerging Markets
- Mobile Finance
---
