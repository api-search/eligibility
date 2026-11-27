---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We operate from the United States; if you access them from elsewhere, you do so on your own initiative and are responsible for compliance with local law.
  entity_types:
  - text: If you use the Services on behalf of an entity, you represent that you are authorized to bind that entity.
    type: business
  minimum_age:
    text: You must be at least 18 years old and have legal capacity to enter into these Terms.
    value: '18'
  restricted_uses:
  - summary: Sanctions, export and AML
    text: Use the Services in violation of sanctions, export control, or anti-money laundering laws
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We are not obligated to accept any prospective client or matter.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Moritz
provenance_date: '2026-11-10'
provider_name: Moritz
provider_slug: moritz
slug: moritz-eligibility
source_date: '2026-11-10'
source_filename: moritz-eligibility.yml
source_heading: Eligibility
source_page: https://www.moritzlegal.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Moritz\naid: moritz\nurl: https://www.moritzlegal.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We operate from the United States; if you access them from elsewhere, you do so on your own initiative and\n    are responsible for compliance with local law.\nentity_types:\n- type: business\n  text: If you use the Services on behalf of an entity, you represent that you are authorized to bind that entity.\nrestricted_uses:\n- summary: Sanctions, export and AML\n  text: Use the Services in violation of sanctions, export control, or anti-money laundering laws\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: true\n  text: We are not obligated to accept any prospective client or matter.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and have legal capacity to enter into these Terms.\n"
source_yaml_url: https://artifacts.apis.io/moritz/eligibility/moritz-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Moritz's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Legal
- Legal Tech
- Law Firms
- Artificial Intelligence
- Contracts
- Y Combinator
---
