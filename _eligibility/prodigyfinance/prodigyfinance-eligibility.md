---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Portal is not intended for distribution to, or use by, any person or entity in any jurisdiction or country where such distribution or use would be contrary to local law or regulation.
  entity_types:
  - text: The Portal is intended solely for users who are 18 years of age or older
    type: individual
  - text: 'If you are a business user: We exclude all implied conditions, warranties, representations or other terms that may apply to our Site or any content on it.'
    type: business
  minimum_age:
    text: The Portal is intended solely for users who are 18 years of age or older, and any registration or use of the Portal by anyone under 18 years of age is unauthorized
    value: '18'
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: Please note that we only provide our Site for domestic and private use. You agree not to use our Site for any commercial or business purposes
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We reserve the right to reject any registration and/or decline any application for a loan.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Prodigy Finance
provenance_date: '2026-11-10'
provider_name: Prodigy Finance
provider_slug: prodigyfinance
slug: prodigyfinance-eligibility
source_date: '2026-11-10'
source_filename: prodigyfinance-eligibility.yml
source_heading: Eligibility
source_page: https://prodigyfinance.com/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prodigy Finance\naid: prodigyfinance\nurl: https://prodigyfinance.com/legal/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Portal is not intended for distribution to, or use by, any person or entity in any jurisdiction or country\n    where such distribution or use would be contrary to local law or regulation.\nentity_types:\n- type: individual\n  text: The Portal is intended solely for users who are 18 years of age or older\n- type: business\n  text: 'If you are a business user: We exclude all implied conditions, warranties, representations or other terms\n  \
  \  that may apply to our Site or any content on it.'\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: Please note that we only provide our Site for domestic and private use. You agree not to use our Site for\n    any commercial or business purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We reserve the right to reject any registration and/or decline any application for a loan.\nminimum_age:\n  value: '18'\n  text: The Portal is intended solely for users who are 18 years of age or older, and any registration or use of\n    the Portal by anyone under 18 years of age is unauthorized\n"
source_yaml_url: https://artifacts.apis.io/prodigyfinance/eligibility/prodigyfinance-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Prodigy Finance's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Lending
- Student Loans
- Education Finance
- Financial Services
---
