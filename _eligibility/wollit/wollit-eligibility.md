---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: be resident in the UK
  entity_types:
  - text: be 18 years or over
    type: individual
  minimum_age:
    text: be 18 years or over
    value: '18'
  restricted_uses:
  - summary: Not for people in bankruptcy, IVA or debt management plan
    text: You’re in bankruptcy, an IVA, or a debt management plan, or have been within the last 12 months.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: if Wollit has been unable to complete identity verification checks to its satisfaction. We have the right to reject any application for Wollit Services at our discretion without giving any reasons for doing so.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Wollit
provenance_date: '2026-11-10'
provider_name: Wollit
provider_slug: wollit
slug: wollit-eligibility
source_date: '2026-11-10'
source_filename: wollit-eligibility.yml
source_heading: Eligibility
source_page: https://www.wollit.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wollit\naid: wollit\nurl: https://www.wollit.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: be resident in the UK\nentity_types:\n- type: individual\n  text: be 18 years or over\nrestricted_uses:\n- summary: Not for people in bankruptcy, IVA or debt management plan\n  text: You’re in bankruptcy, an IVA, or a debt management plan, or have been within the last 12 months.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: if Wollit has been unable to complete identity verification checks to its satisfaction. We have the right\n    to reject\
  \ any application for Wollit Services at our discretion without giving any reasons for doing so.\nminimum_age:\n  value: '18'\n  text: be 18 years or over\n"
source_yaml_url: https://artifacts.apis.io/wollit/eligibility/wollit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Wollit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Credit
- Credit Building
- Personal Finance
- Consumer Finance
- United Kingdom
- Rent Reporting
---
