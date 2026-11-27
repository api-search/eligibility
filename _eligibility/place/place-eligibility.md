---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By agreeing to these Terms, you represent that you are at least 18 years old and are otherwise legally qualified to enter into contracts under applicable law.
    type: individual
  - text: Any individual using the Services on behalf of a corporate entity or business further represents and warrants that they are authorized to act and enter into contracts on behalf of said corporate entity or business.
    type: business
  minimum_age:
    text: you represent that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Prohibited uses
    text: use the Website or Services for unauthorized, unlawful or unethical purposes
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
name: PLACE
provenance_date: '2026-11-10'
provider_name: PLACE
provider_slug: place
slug: place-eligibility
source_date: '2026-11-10'
source_filename: place-eligibility.yml
source_heading: Eligibility
source_page: https://place.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PLACE\naid: place\nurl: https://place.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By agreeing to these Terms, you represent that you are at least 18 years old and are otherwise legally qualified\n    to enter into contracts under applicable law.\n- type: business\n  text: Any individual using the Services on behalf of a corporate entity or business further represents and warrants\n    that they are authorized to act and enter into contracts on behalf of said corporate entity or business.\nrestricted_uses:\n- summary:\
  \ Prohibited uses\n  text: use the Website or Services for unauthorized, unlawful or unethical purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/place/eligibility/place-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from PLACE's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- PropTech
- CRM
- Transaction Management
- Brokerage
- MLS
- Mortgage
- Title and Escrow
- Business Services
- Identity
---
