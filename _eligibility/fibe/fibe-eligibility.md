---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent and warrant that you are of the age of majority as per the applicable laws to which you are subject to and are competent to understand, enter into, and comply with these Terms
    type: individual
  minimum_age:
    text: you represent and warrant that you are of the age of majority as per the applicable laws to which you are subject to
    value: age of majority
  restricted_uses:
  - summary: Unlawful or fraudulent use
    text: use the Platform or the Services for committing fraud, embezzlement, money laundering, or for any unlawful and/or illegal purposes
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: The Company reserves the right to accept or reject your registration for the Services without obligation of explanation.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fibe
provenance_date: '2026-11-09'
provider_name: Fibe
provider_slug: fibe
slug: fibe-eligibility
source_date: '2026-11-09'
source_filename: fibe-eligibility.yml
source_heading: Eligibility
source_page: https://www.fibe.in/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fibe\naid: fibe\nurl: https://www.fibe.in/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you represent and warrant that you are of the age of majority as per the applicable laws to which you are\n    subject to and are competent to understand, enter into, and comply with these Terms\nrestricted_uses:\n- summary: Unlawful or fraudulent use\n  text: use the Platform or the Services for committing fraud, embezzlement, money laundering, or for any unlawful\n    and/or illegal purposes\nverification:\n  kyc: true\n  kyb:\
  \ null\n  approval_required: true\n  text: The Company reserves the right to accept or reject your registration for the Services without obligation\n    of explanation.\nminimum_age:\n  value: age of majority\n  text: you represent and warrant that you are of the age of majority as per the applicable laws to which you are\n    subject to\n"
source_yaml_url: https://artifacts.apis.io/fibe/eligibility/fibe-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Fibe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Lending
- Personal Loans
- Consumer Finance
- India
- Credit
- MCP
- Agents
---
