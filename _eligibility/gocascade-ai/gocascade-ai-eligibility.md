---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer desires to license Cascade AI and make Cascade AI available to its employees
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No professional advice reliance
    text: CUSTOMER SHALL NOT, AND SHALL ENSURE THAT ITS EMPLOYEES DO NOT, RELY ON CASCADE AI FOR ANY MEDICAL, HEALTH, SAFETY, LEGAL, TAX, FINANCIAL, OR OTHER PROFESSIONAL ADVICE.
  - summary: No protected health information
    text: Customer represents and warrants that it will not disclose any protected health information to Cascade without the prior written consent of Cascade.
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
name: Cascade
provenance_date: '2026-11-09'
provider_name: Cascade
provider_slug: gocascade-ai
slug: gocascade-ai-eligibility
source_date: '2026-11-09'
source_filename: gocascade-ai-eligibility.yml
source_heading: Eligibility
source_page: https://gocascade.ai/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cascade\naid: gocascade-ai\nurl: https://gocascade.ai/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer desires to license Cascade AI and make Cascade AI available to its employees\nrestricted_uses:\n- summary: No professional advice reliance\n  text: CUSTOMER SHALL NOT, AND SHALL ENSURE THAT ITS EMPLOYEES DO NOT, RELY ON CASCADE AI FOR ANY MEDICAL, HEALTH,\n    SAFETY, LEGAL, TAX, FINANCIAL, OR OTHER PROFESSIONAL ADVICE.\n- summary: No protected health information\n  text: Customer represents and warrants\
  \ that it will not disclose any protected health information to Cascade without\n    the prior written consent of Cascade.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gocascade-ai/eligibility/gocascade-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Cascade's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Enterprise
- Human Resources
- IT
- Automation
- Company
---
