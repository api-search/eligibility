---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer will not use the Services, or permit access, from embargoed countries or by denied or restricted parties
  entity_types:
  - text: If Customer is an entity, organization, or company, the individual accepting these Terms represents and warrants that they have full corporate power and authority to bind Customer to this Agreement.
    type: business
  minimum_age:
    text: By agreeing to these Terms, you represent and warrant that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: Customer will not use the Services, or permit access, from embargoed countries or by denied or restricted parties, and will not submit export-controlled data without Hadrius’s prior written consent.
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
name: Hadrius
provenance_date: '2026-11-09'
provider_name: Hadrius
provider_slug: hadrius
slug: hadrius-eligibility
source_date: '2026-11-09'
source_filename: hadrius-eligibility.yml
source_heading: Eligibility
source_page: https://app.hadrius.com/docs/Hadrius%20Terms%20of%20Service.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hadrius\naid: hadrius\nurl: https://app.hadrius.com/docs/Hadrius%20Terms%20of%20Service.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer will not use the Services, or permit access, from embargoed countries or by denied or restricted\n    parties\nentity_types:\n- type: business\n  text: If Customer is an entity, organization, or company, the individual accepting these Terms represents and\n    warrants that they have full corporate power and authority to bind Customer to this Agreement.\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: Customer\
  \ will not use the Services, or permit access, from embargoed countries or by denied or restricted\n    parties, and will not submit export-controlled data without Hadrius’s prior written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By agreeing to these Terms, you represent and warrant that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/hadrius/eligibility/hadrius-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Hadrius's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Compliance
- RegTech
- Financial Services
- SEC
- FINRA
- Governance
- Risk and Compliance
---
