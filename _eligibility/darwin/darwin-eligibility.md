---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is available only to individuals who (a) are at least sixteen (16) years old
    type: individual
  - text: possess the legal capacity to enter into these Terms (on behalf of themselves and their organization, as applicable)
    type: business
  minimum_age:
    text: The Site is available only to individuals who (a) are at least sixteen (16) years old
    value: '16'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: (a) use the Site and/or the Content for any illegal, immoral, unlawful and/or unauthorized purposes;
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
name: Darwin
provenance_date: '2026-11-09'
provider_name: Darwin
provider_slug: darwin
slug: darwin-eligibility
source_date: '2026-11-09'
source_filename: darwin-eligibility.yml
source_heading: Eligibility
source_page: https://www.darwingov.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Darwin\naid: darwin\nurl: https://www.darwingov.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is available only to individuals who (a) are at least sixteen (16) years old\n- type: business\n  text: possess the legal capacity to enter into these Terms (on behalf of themselves and their organization, as\n    applicable)\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: (a) use the Site and/or the Content for any illegal, immoral, unlawful and/or unauthorized purposes;\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The Site is available only to individuals who (a) are at least sixteen (16) years old\n"
source_yaml_url: https://artifacts.apis.io/darwin/eligibility/darwin-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Darwin's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Government
- Artificial Intelligence
- AI Governance
- Public Sector
- Compliance
- GovTech
- Policy
---
