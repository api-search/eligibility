---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Paycheck City and Paycheck City Payroll are designed for use by residents of the United States only.
  entity_types:
  - text: is intended by us to be directed only at individual consumers and not employers or organizations.
    type: individual
  minimum_age:
    text: You must be 13 years of age or older to visit or use the Site.
    value: '13'
  restricted_uses:
  - summary: Commercial or for-profit use
    text: solely for your personal use but not for any for-profit or commercial activities or purposes or for resale.
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
name: Symmetry
provenance_date: '2026-11-10'
provider_name: Symmetry
provider_slug: symmetry
slug: symmetry-eligibility
source_date: '2026-11-10'
source_filename: symmetry-eligibility.yml
source_heading: Eligibility
source_page: https://www.symmetry.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Symmetry\naid: symmetry\nurl: https://www.symmetry.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Paycheck City and Paycheck City Payroll are designed for use by residents of the United States only.\nentity_types:\n- type: individual\n  text: is intended by us to be directed only at individual consumers and not employers or organizations.\nrestricted_uses:\n- summary: Commercial or for-profit use\n  text: solely for your personal use but not for any for-profit or commercial activities or purposes or for resale.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 years of age or older to visit or use the Site.\n"
source_yaml_url: https://artifacts.apis.io/symmetry/eligibility/symmetry-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Symmetry's own page on 2026-11-10.
synthetic: false
tags:
- Payroll Tax Compliance
- Payroll Platforms
- Employer of Record
- PEO
- Recruiting
- Staffing
- Large Employers
- Tax APIs
---
