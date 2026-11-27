---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No access by direct competitors
    text: You may not access the AI Gateway or request information from our AI Gateway if you are a direct competitor of Cequence, except with our prior written consent.
  - summary: No disruptive or unauthorized use
    text: interfere with or disrupt the integrity or performance of the Early Access Services or third-party data contained therein
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
name: Cequence Security
provenance_date: '2026-11-09'
provider_name: Cequence Security
provider_slug: cequence
slug: cequence-eligibility
source_date: '2026-11-09'
source_filename: cequence-eligibility.yml
source_heading: Eligibility
source_page: https://www.cequence.ai/legal/saas-ai-gateway-end-user-license-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cequence Security\naid: cequence\nurl: https://www.cequence.ai/legal/saas-ai-gateway-end-user-license-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No access by direct competitors\n  text: You may not access the AI Gateway or request information from our AI Gateway if you are a direct competitor\n    of Cequence, except with our prior written consent.\n- summary: No disruptive or unauthorized use\n  text: interfere with or disrupt the integrity or performance of the Early Access Services or third-party data\n    contained\
  \ therein\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cequence/eligibility/cequence-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Cequence Security's own page on 2026-11-09.
synthetic: false
tags:
- AI Protection
- API Discovery
- API Security
- Application Security
- Attack Surface
- Bot Management
- Business Logic Abuse
- CNAPP
- Cybersecurity
- Fraud Prevention
- Unified API Protection
---
