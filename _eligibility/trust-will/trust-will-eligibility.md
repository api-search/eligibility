---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU AGREE THAT BY USING THE SERVICES YOU ARE AT LEAST 18 YEARS OF AGE AND/OR YOU ARE LEGALLY ABLE TO ENTER INTO A CONTRACT.
    type: individual
  minimum_age:
    text: YOU AGREE THAT BY USING THE SERVICES YOU ARE AT LEAST 18 YEARS OF AGE AND/OR YOU ARE LEGALLY ABLE TO ENTER INTO A CONTRACT.
    value: '18'
  restricted_uses:
  - summary: Not legal advice / self-help only
    text: TRUST & WILL IS NOT A LAW FIRM, AND DOES NOT PROVIDE LEGAL ADVICE.
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
name: Trust & Will
provenance_date: '2026-11-10'
provider_name: Trust & Will
provider_slug: trust-will
slug: trust-will-eligibility
source_date: '2026-11-10'
source_filename: trust-will-eligibility.yml
source_heading: Eligibility
source_page: https://trustandwill.com/security/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trust & Will\naid: trust-will\nurl: https://trustandwill.com/security/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: YOU AGREE THAT BY USING THE SERVICES YOU ARE AT LEAST 18 YEARS OF AGE AND/OR YOU ARE LEGALLY ABLE TO ENTER\n    INTO A CONTRACT.\nrestricted_uses:\n- summary: Not legal advice / self-help only\n  text: TRUST & WILL IS NOT A LAW FIRM, AND DOES NOT PROVIDE LEGAL ADVICE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU AGREE\
  \ THAT BY USING THE SERVICES YOU ARE AT LEAST 18 YEARS OF AGE AND/OR YOU ARE LEGALLY ABLE TO ENTER\n    INTO A CONTRACT.\n"
source_yaml_url: https://artifacts.apis.io/trust-will/eligibility/trust-will-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Trust & Will's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Estate Planning
- Wills And Trusts
- Probate
- Legal
- Financial Services
- Wealth Management
- Fintech
---
