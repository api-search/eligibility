---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The services offered by Lower and this website are intended for U.S. residents only and only in those states where Lower is duly licensed to originate mortgage loans.
  entity_types:
  - text: To qualify for a mortgage, borrowers must be U.S. citizens or permanent residents
    type: individual
  minimum_age:
    text: You will only access or use this website and transact business with Lower if you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: Is in any way unlawful or prohibited, or that is harmful or destructive to anyone or their property
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
name: Lower
provenance_date: '2026-11-09'
provider_name: Lower
provider_slug: lower
slug: lower-eligibility
source_date: '2026-11-09'
source_filename: lower-eligibility.yml
source_heading: Eligibility
source_page: https://www.lower.com/legal/website-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lower\naid: lower\nurl: https://www.lower.com/legal/website-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The services offered by Lower and this website are intended for U.S. residents only and only in those states\n    where Lower is duly licensed to originate mortgage loans.\nentity_types:\n- type: individual\n  text: To qualify for a mortgage, borrowers must be U.S. citizens or permanent residents\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: Is in any way unlawful or prohibited, or that is harmful or destructive to anyone or their property\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You will only access or use this website and transact business with Lower if you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/lower/eligibility/lower-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Lower's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Services
- Mortgage
- Lending
- Home Loans
- Refinance
- Home Equity
- Real Estate
- Fintech
---
