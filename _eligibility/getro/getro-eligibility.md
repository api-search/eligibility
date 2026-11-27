---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are of legal age to form a binding contract and are not barred from doing so under any applicable laws.
    type: individual
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization or entity’s behalf
    type: business
  minimum_age:
    text: if you are a child under 13, please do not use our Services
    value: '13'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: Violates any law or regulation, including any applicable export control laws
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
name: Getro
provenance_date: '2026-11-09'
provider_name: Getro
provider_slug: getro
slug: getro-eligibility
source_date: '2026-11-09'
source_filename: getro-eligibility.yml
source_heading: Eligibility
source_page: https://www.getro.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Getro\naid: getro\nurl: https://www.getro.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are of legal age to form a binding contract and are not barred from doing\n    so under any applicable laws.\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization or entity’s behalf\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: Violates any\
  \ law or regulation, including any applicable export control laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: if you are a child under 13, please do not use our Services\n"
source_yaml_url: https://artifacts.apis.io/getro/eligibility/getro-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Getro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Job
- Talent
- Hiring
- Recruiting
- Job Board
- Venture Capital
- Networks
- CRM
---
