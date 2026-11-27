---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Service for use only by persons located in the United States.
  minimum_age:
    text: This Service is offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Decisions with legal effects
    text: (vii) use Output as the sole basis for decisions with significant legal or similarly consequential effects on individuals without appropriate human review and compliance with applicable law.
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
name: elvex
provenance_date: '2026-11-09'
provider_name: elvex
provider_slug: elvex
slug: elvex-eligibility
source_date: '2026-11-09'
source_filename: elvex-eligibility.yml
source_heading: Eligibility
source_page: https://www.elvex.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: elvex\naid: elvex\nurl: https://www.elvex.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Service for use only by persons located in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Decisions with legal effects\n  text: (vii) use Output as the sole basis for decisions with significant legal or similarly consequential effects\n    on individuals without appropriate human review and compliance with applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n \
  \ text: This Service is offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/elvex/eligibility/elvex-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from elvex's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Enterprise
- Platform
- Automation
- Integration
- Company
---
