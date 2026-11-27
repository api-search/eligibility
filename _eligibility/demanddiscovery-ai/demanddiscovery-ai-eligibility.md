---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and legally able to enter into these Terms to purchase a paid plan.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and legally able to enter into these Terms to purchase a paid plan.
    value: '18'
  restricted_uses:
  - summary: Lawful outreach only
    text: violate applicable laws or regulations, including anti-spam laws (such as CAN-SPAM, CASL, and GDPR) when sending outreach
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
name: Demand Discovery AI
provenance_date: '2026-11-09'
provider_name: Demand Discovery AI
provider_slug: demanddiscovery-ai
slug: demanddiscovery-ai-eligibility
source_date: '2026-11-09'
source_filename: demanddiscovery-ai-eligibility.yml
source_heading: Eligibility
source_page: https://demanddiscovery.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Demand Discovery AI\naid: demanddiscovery-ai\nurl: https://demanddiscovery.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally able to enter into these Terms to purchase a paid plan.\nrestricted_uses:\n- summary: Lawful outreach only\n  text: violate applicable laws or regulations, including anti-spam laws (such as CAN-SPAM, CASL, and GDPR) when\n    sending outreach\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text:\
  \ You must be at least 18 years old and legally able to enter into these Terms to purchase a paid plan.\n"
source_yaml_url: https://artifacts.apis.io/demanddiscovery-ai/eligibility/demanddiscovery-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Demand Discovery AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Startup Idea Validation
- Market Research
- Demand Discovery
- Artificial Intelligence
- MCP
- Customer Discovery
---
